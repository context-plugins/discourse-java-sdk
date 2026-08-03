# Backups

```java
BackupsApi backupsApi = client.getBackupsApi();
```

## Class Name

`BackupsApi`

## Methods

* [Get Backups](../../doc/controllers/backups.md#get-backups)
* [Create Backup](../../doc/controllers/backups.md#create-backup)
* [Send Download Backup Email](../../doc/controllers/backups.md#send-download-backup-email)
* [Download Backup](../../doc/controllers/backups.md#download-backup)


# Get Backups

```java
CompletableFuture<ApiResponse<List<AdminBackupsJsonResponse>>> getBackupsAsync()
```

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`List<AdminBackupsJsonResponse>`](../../doc/models/admin-backups-json-response.md).

## Example Usage

```java
backupsApi.getBackupsAsync().thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Create Backup

```java
CompletableFuture<ApiResponse<AdminBackupsJsonResponse1>> createBackupAsync(
    final AdminBackupsJsonRequest body)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `body` | [`AdminBackupsJsonRequest`](../../doc/models/admin-backups-json-request.md) | Body, Optional | - |

## Response Type

**200**: success response

This method returns an [`ApiResponse`](../../doc/api-response.md) instance. The `getResult()` getter of this instance returns the response data which is of type [`AdminBackupsJsonResponse1`](../../doc/models/admin-backups-json-response-1.md).

## Example Usage

```java
backupsApi.createBackupAsync(null).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Send Download Backup Email

```java
CompletableFuture<ApiResponse<Void>> sendDownloadBackupEmailAsync(
    final String filename)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `filename` | `String` | Template, Required | - |

## Response Type

**200**: success response

`void`

## Example Usage

```java
String filename = "filename2";

backupsApi.sendDownloadBackupEmailAsync(filename).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```


# Download Backup

```java
CompletableFuture<ApiResponse<Void>> downloadBackupAsync(
    final String filename,
    final String token)
```

## Parameters

| Parameter | Type | Tags | Description |
|  --- | --- | --- | --- |
| `filename` | `String` | Template, Required | - |
| `token` | `String` | Query, Required | - |

## Response Type

**200**: success response

`void`

## Example Usage

```java
String filename = "filename2";
String token = "token6";

backupsApi.downloadBackupAsync(filename, token).thenAccept(result -> {
    // TODO success callback handler
    System.out.println(result);
}).exceptionally(exception -> {
    // TODO failure callback handler
    exception.printStackTrace();
    return null;
});
```

