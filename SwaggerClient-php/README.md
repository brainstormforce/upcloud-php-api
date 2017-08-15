# SwaggerClient-php
Upcloud api specification

This PHP package is automatically generated by the [Swagger Codegen](https://github.com/swagger-api/swagger-codegen) project:

- API version: 1.0.0
- Build package: io.swagger.codegen.languages.PhpClientCodegen

## Requirements

PHP 5.5 and later

## Installation & Usage
### Composer

To install the bindings via [Composer](http://getcomposer.org/), add the following to `composer.json`:

```
{
  "repositories": [
    {
      "type": "git",
      "url": "https://github.com/GIT_USER_ID/GIT_REPO_ID.git"
    }
  ],
  "require": {
    "GIT_USER_ID/GIT_REPO_ID": "*@dev"
  }
}
```

Then run `composer install`

### Manual Installation

Download the files and include `autoload.php`:

```php
    require_once('/path/to/SwaggerClient-php/vendor/autoload.php');
```

## Tests

To run the unit tests:

```
composer install
./vendor/bin/phpunit
```

## Getting Started

Please follow the [installation procedure](#installation--usage) and then run the following:

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$api_instance = new Swagger\Client\Api\ServerApi();

try {
    $result = $api_instance->serverGet();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling ServerApi->serverGet: ', $e->getMessage(), PHP_EOL;
}

?>
```

## Documentation for API Endpoints

All URIs are relative to *http://localhost/1.2*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*ServerApi* | [**serverGet**](docs/Api/ServerApi.md#serverget) | **GET** /server | List of servers
*ServerApi* | [**serverPost**](docs/Api/ServerApi.md#serverpost) | **POST** /server | Create server
*ServerApi* | [**serverServerIdDelete**](docs/Api/ServerApi.md#serverserveriddelete) | **DELETE** /server/{serverId} | Delete server
*ServerApi* | [**serverServerIdGet**](docs/Api/ServerApi.md#serverserveridget) | **GET** /server/{serverId} | Server details
*ServerApi* | [**serverServerIdPut**](docs/Api/ServerApi.md#serverserveridput) | **PUT** /server/{serverId} | Modify server
*StorageApi* | [**storageGet**](docs/Api/StorageApi.md#storageget) | **GET** /storage | List of storages


## Documentation For Models

 - [BackupRule](docs/Model/BackupRule.md)
 - [Error](docs/Model/Error.md)
 - [ErrorCode](docs/Model/ErrorCode.md)
 - [ErrorError](docs/Model/ErrorError.md)
 - [ErrorStatus](docs/Model/ErrorStatus.md)
 - [InlineResponse200](docs/Model/InlineResponse200.md)
 - [InlineResponse2001](docs/Model/InlineResponse2001.md)
 - [InlineResponse2002](docs/Model/InlineResponse2002.md)
 - [InlineResponse2002Storages](docs/Model/InlineResponse2002Storages.md)
 - [InlineResponse200Servers](docs/Model/InlineResponse200Servers.md)
 - [IpAddress](docs/Model/IpAddress.md)
 - [Server](docs/Model/Server.md)
 - [ServerIpAddresses](docs/Model/ServerIpAddresses.md)
 - [ServerStorageDevices](docs/Model/ServerStorageDevices.md)
 - [ServerTags](docs/Model/ServerTags.md)
 - [Storage](docs/Model/Storage.md)
 - [StorageBackups](docs/Model/StorageBackups.md)
 - [StorageDevice](docs/Model/StorageDevice.md)
 - [StorageServers](docs/Model/StorageServers.md)


## Documentation For Authorization

 All endpoints do not require authorization.


## Author



