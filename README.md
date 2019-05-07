# ![LOGO](logo.png) Route Optimization **flow**ground Connector

## Description

A generated **flow**ground connector for the Route Optimization API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/graphhopper.com/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:42:13+03:00

## API Description

Our Route Optimization API solves the so called vehicle routing problem fast. It calculates an optimal tour for a set of vehicles, services and constraints

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Solves vehicle routing problems

> This endpoint for solving vehicle routing problems, i.e. traveling salesman or vehicle routing problems, and returns the solution.

*Tags:* `vrp`

#### Input Parameters
* `key` - _required_ - your API key

### Return the solution associated to the jobId

> This endpoint returns the solution of a large problems. You can fetch it with the job_id, you have been sent.

*Tags:* `solution`

#### Input Parameters
* `key` - _required_ - your API key
* `jobId` - _required_ - Request solution with jobId

## License

**flow**ground :- Telekom iPaaS / graphhopper-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
