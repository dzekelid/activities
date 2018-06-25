---
name: MySpace Developers
x-slug: myspace-developers
description: 'AskMyspace: http://askmyspace.com  Twitter: http://twitter.com/Myspace  Instagram:
  http://instagram.com/Myspace  Tumblr: http://myspace.tumblr.com  YouTube: http://www.youtube.com/Myspace'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
x-kinRank: "7"
x-alexaRank: "4691"
tags: Activities
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/myspace-developers/apis.md
specificationVersion: "0.14"
apis:
- name: My Space Get Activities Personid Selector Appid
  x-api-slug: my-space
  description: Retrieves activities created by an application.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/activities/{personId}/{selector}/{appId}
  tags: Activities,People,Selector,AppId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/myspace-developers/1-0activitiespersonidselectorappid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/myspace-developers/1-0activitiespersonidselectorappid-get-openapi.md
- name: My Space Get Activities Supported Object Types
  x-api-slug: my-space
  description: Retrieves all supported object types.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/activities/@supportedObjectTypes
  tags: Activities,Supported,ObjectTypes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/myspace-developers/1-0activitiessupportedobjecttypes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/myspace-developers/1-0activitiessupportedobjecttypes-get-openapi.md
- name: My Space Get Activities Supported Verbs
  x-api-slug: my-space
  description: Retrieves all supported verbs.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/activities/@supportedVerbs
  tags: Activities,Supported,Verbs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/myspace-developers/1-0activitiessupportedverbs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/myspace-developers/1-0activitiessupportedverbs-get-openapi.md
- name: My Space Get Activities Supported Fields
  x-api-slug: my-space
  description: Retrieves all supported fields.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/activities/@supportedFields
  tags: Activities,Supported,Fields
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/myspace-developers/1-0activitiessupportedfields-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/myspace-developers/1-0activitiessupportedfields-get-openapi.md
- name: My Space Post Activities Personid Self
  x-api-slug: my-space
  description: Creates an activity for the user.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/activities/{personId}/@self
  tags: Activities,People,Self
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/myspace-developers/1-0activitiespersonidself-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/myspace-developers/1-0activitiespersonidself-post-openapi.md
- name: My Space Get Activities Personid Selector
  x-api-slug: my-space
  description: Retrieves all activities for the user or for the friends of the viewer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/activities/{personId}/{selector}
  tags: Activities,People,Selector
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/myspace-developers/1-0activitiespersonidselector-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/myspace-developers/1-0activitiespersonidselector-get-openapi.md
- name: My Space
  x-api-slug: my-space
  description: 'AskMyspace: http://askmyspace.com  Twitter: http://twitter.com/Myspace  Instagram:
    http://instagram.com/Myspace  Tumblr: http://myspace.tumblr.com  YouTube: http://www.youtube.com/Myspace'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com//
  tags: Activities
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/myspace-developers/openapi.md
x-common:
- type: x-website
  url: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
- type: x-blog
  url: http://www.myspace.com/pressroom?url=/company+blog/
- type: x-blog-rss
  url: http://myspace.tekgroupweb.com/company+blog/rss.xml
- type: x-crunchbase
  url: http://www.crunchbase.com/company/myspace
- type: x-crunchbase
  url: https://crunchbase.com/organization/myspace
- type: x-github
  url: https://github.com/myspace
- type: x-twitter
  url: https://twitter.com/#!/MySpaceDevTeam
- type: x-twitter
  url: https://twitter.com/Myspace
- type: x-website
  url: http://myspace.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---