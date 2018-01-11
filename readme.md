# Epi meeting

## Attendees
- Brian
- Dylan
- RJ
- Chris?

Episerver Bootcamp?

## Sitecore Problems

- No component library
- No solution structure
- Model first approach

## Bullet List of things to Accomplish

- Scaffolding?
  - Episerver has a new solution template
  - Just creats a new solution based on MVC standards and adds nuget reference
  - Epi 'scaffolding' doesn't enforce solution structure
- Unit Testing Framework?
- Framework agnostic components

## Epi License

- On Prem
  - Limited to ~5 sites
  - Each code base would need it's own license, each code base has it's own app pool
  - 1 license per code-base
  - 1 code base per episerver install
- Cloud
  - Unlimited sites
  - PaaS offering
  - Code base lives in azure webapp
  - Deploy from VS to Azure directly
  - 1 deployment unit == 1 app

Alloy is a free repo that can be cloned and ran without a license.  Just clone from github.

Episerver ~ Sitecore:
Content Area ~ Placeholder
Blocks ~ Snippets
Shared Blocks vs Local Blocks - plays into content editing experience.  Macros vs References?
Page Type ~ Page Template
Page Template ~ MVC Razer View / Controller Action

All (most?) C# classes implement IContent

## Resources

- http://cjsharp.com
- http://world.episerver.com/
- http://world.episerver.com/digital-experience-cloud-service/
- http://world.episerver.com/documentation/Episerver-technical-overview/
- http://world.episerver.com/documentation/getting-started/
- http://world.episerver.com/documentation/videos/
- http://world.episerver.com/articles/Items/EPiServer-Continuous-Release-Process/
- http://world.episerver.com/documentation/developer-guides/
- https://github.com/episerver
- https://gregwiechec.com
- Demo site for search: Google `QJet`

## Missing in core code:

- Block preview mechanism
- Template Coordinator
- No best practice on multi tenancy
  - _can_ be accomplished with areas, but doesn't have to be.  Potentially a place where a framework could help?
- Episerver Instant Templates?  Created by another partner, not used often.
- SCORE.Core, SCORE.Templates? What are the things that you install on a new epi solution?
- How do you distribute components without distributing the source?
- Nuget package that contains all of the base functionality of a site: seo, error handling, etc

Ramp up on Commerce and B2B Tech!
