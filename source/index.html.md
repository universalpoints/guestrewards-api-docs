---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - ruby

toc_footers:
  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true
---

# Introduction

API Documentation for Guestbook White Label

**Current Version:**<br> Alpha 1.0

**NOTES:**<br>
 - This documentation has not been finalized and is still a work in progress.

**TODO:**<br>
 - Provision test environment.<br>
 - Add API authorization (JWT, white list server IP)

# Authentication

TBD

# Account Information

## Get Pending & Available Balance

```ruby
 # TODO add ruby example
```

> The endpoint returns JSON structured like this:

```json
{
    "pending": "$40.32",
    "available": "$123.67"
}
```

Retrieve Pending and Available balance for an SH Group Loyalty Member.

### HTTP Request

`GET https://api.guestrewards.com/v1/account/balance`

### Headers
Content-Type: application/json

### Query Parameters

Parameter | type | Default | Description
--------- | ---- | ------- | -----------
cendyn_account_token | String | nil | https://crmapiqa.cendyn.com/swagger/ui/index#!/Account/Account_Login

