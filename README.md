# Static Marketing Site Tools

> My personal curated shortlist of tools for making static marketing sites

## Static site generators

- [Middleman](https://middlemanapp.com) -- Battle-tested and feature-rich, but written in Ruby. If you want to use something like webpack for js dependencies, things get a little clunkier than I would like. 
- [Spike](https://spike.js.org) -- Super simple and modern build tool geared around using the latest HTML, CSS and JS specs where possible. Very focused on marketing pages with no out-of-the-box blog functionality, but built-in typographic enhancements via `smartypants`. The template processor is a little fragile and doesn't give the best feedback, but I like the simplicity of this tool. Built and formerly used at [Carrot](https://carrot.com), though it seems to no longer be maintained. Powered by webpack.
- [GoPablo](https://spike.js.org) -- *(I have not tried this yet.)* Interesting new static site generator, apparently used by Swiss design agency [Riangle](https://www.riangle.com). [Luan](https://github.com/luangjokaj), the author, also has a neat-looking HTML email build tool called [fuzzymail](https://www.fuzzymail.co). 

## Hosting

- [AWS](https://aws.amazon.com) S3 + CloudFront + Lambda + API Gateway + DynamoDB + SES... -- Powerful and flexible but complicated to setup and maintain.
- [Netlify](https://www.netlify.com) -- Super easy, does everything I need. Forms and backend-only analytics are nice add-ons. 
- [Zeit](https://zeit.co) -- Similar to Netlify, but they seem less popular, and they don't have as many add-on features like forms and backend-only analytics. They do, however, provide a very easy-to-use FaaS platform (built on Lambda?) which can be used for things like forms. Very nice CLI.

## Headless CMS
(Often a CMS isn't needed, but in case it is...)

- [NetlifyCMS](https://www.netlifycms.org) -- Free and open source. Seems solid, but requires a GitHub account and I read somewhere that it doesn't work on mobile. 
- [Forestry](https://forestry.io) -- *(I have not tried this yet.)* Headless CMS with a free tier that doesn't require the use of a GitHub account. This can make on-boarding non-developers somewhat easier. 
- [Contentful](https://www.contentful.com) -- Expensive and flexible.

## Other tools

- [Affinity Designer](https://affinity.serif.com/en-gb/designer/) -- Great vector design app with support for symbols, global colors, constraints for resizing, and so on. Super fast and fluid to use, with great exporting tools. Full version available on Mac, Windows and iPad. Seems to give Sketch a run for its money, but unfortunately it doesn't support importing Sketch files yet. 
- [Pattern Lab](https://patternlab.io) -- *(I have not tried this yet.)* Looks like sort of a cross between a traditional static site builder, a design tool, a prototyping tool, and a design system documentation/collaboration platform. Designed by [Brad Frost](https://bradfrost.com) to support his practice of [atomic design](http://atomicdesign.bradfrost.com). 
