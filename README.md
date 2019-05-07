# ![LOGO](logo.png) TimesTags **flow**ground Connector

## Description

A generated **flow**ground connector for the TimesTags API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/nytimes.com/times_tags/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:21+03:00

## API Description

With the TimesTags API, you can mine the riches of the New York Times tag set. The TimesTags service matches your query to the controlled vocabularies that fuel NYTimes.com metadata. You supply a string of characters, and the service returns a ranked list of suggested terms.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### get_timestags

#### Input Parameters
* `query` - _required_ - Your search query
* `filter` - _optional_ - If you do not specify a value for filter (see the Optional Parameters), your query will be matched to tags in all four Times dictionaries: subject, geographic location, organization and person. To use more than one, separate with commas.

    Possible values: Des, Geo, Org, Per.
* `max` - _optional_ - Sets the maximum number of results

## License

**flow**ground :- Telekom iPaaS / nytimes-com-times-tags-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
