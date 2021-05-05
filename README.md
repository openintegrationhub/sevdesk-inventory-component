# ![LOGO](logo.png) sevDesk Inventory API OIH Connector

## Description

[![Generic badge](https://img.shields.io/badge/Status-NotTested!-lightgrey.svg)](https://shields.io/)

A generated OIH connector for the sevDesk Inventory API (version 2.0.0).

Generated from: https://my.sevdesk.de/api/v1<br/>
Generated at: 2021-04-22T22:43:35+02:00

## API Description

## Authorization

Supported authorization schemes:

- API Key

## Actions

### Retrieve parts

> Retrieve all parts in your sevDesk inventory according to the applied filters.<br/>

_Tags:_ `Part`

#### Input Parameters

- `partNumber` - _optional_ - Retrieve all parts with this part number<br/>
- `name` - _optional_ - Retrieve all parts with this name<br/>

### Create a new part

> Creates a part in your sevDesk inventory.<br/>

_Tags:_ `Part`

### Find part by ID

> Returns a single part<br/>

_Tags:_ `Part`

#### Input Parameters

- `partId` - _required_ - ID of part to return<br/>

### Update an existing part

> Update a part<br/>

_Tags:_ `Part`

#### Input Parameters

- `partId` - _required_ - ID of part to update<br/>

### Get stock of a part

> Returns the current stock amount of the given part.<br/>

_Tags:_ `Part`

#### Input Parameters

- `partId` - _required_ - ID of part for which you want the current stock.<br/>

## License

: sevDeskInventory-Component<br/>
<br/>

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
