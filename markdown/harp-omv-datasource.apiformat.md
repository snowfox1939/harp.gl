<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-omv-datasource](./harp-omv-datasource.md) &gt; [APIFormat](./harp-omv-datasource.apiformat.md)

## APIFormat enum

<b>Signature:</b>

```typescript
export declare enum APIFormat 
```

## Enumeration Members

|  Member | Value | Description |
|  --- | --- | --- |
|  HereV1 | <code>0</code> | Use the REST API format of HERE Vector Tiles Server component version 1.<!-- -->Documentation: https://developer.here.com/documentation/vector-tiles-api/dev\_guide/index.html<!-- -->Usage:<!-- -->&lt;<!-- -->OmvRestClientParams.baseUrl<!-- -->&gt;<!-- -->/<zoom>/<X>/<Y>/omv<!-- -->If \[\[OmvRestClientParams.authenticationToken\]\] is provided, it will be added as HTTP header:<!-- -->Authorization: Bearer $authenticationToken<!-- -->Format definition: <code>//http&#124;s://&lt;base-url&gt;/{API version}/{layers}/{projection}/{z}/{x}/{y}/{format}</code>Default authentication method used: \[\[AuthenticationTypeBearer\]\]. |
|  MapboxV4 | <code>1</code> | Use the REST API format of Mapbox Vector Tile API v4.<!-- -->Usage: <code>&lt;OmvRestClientParams.baseUrl&gt;/&lt;zoom&gt;/&lt;X&gt;/&lt;Y&gt;.mvt?access_token=&lt;OmvRestClientParams.authenticationCode&gt;</code>Format definition: <code>http&#124;s://&lt;base-url&gt;/v4/{map_id}/{z}/{x}/{y}{@2x}.{format}?[style]&amp;access_token={access_token}</code>Sample URL: <code>http://a.tiles.mapbox.com/v4/mapbox.mapbox-streets-v7/14/4823/6160.mvt?access_token=your-mapbox-access-token</code>Default authentication method used: \[\[AuthenticationTypeAccessToken\]\]. |
|  TomtomV1 | <code>5</code> | Use the REST API format of Tomtoms Vector Tile API v1.<!-- -->Usage: <code>&lt;OmvRestClientParams.baseUrl&gt;/&lt;zoom&gt;/&lt;X&gt;/&lt;Y&gt;.pbf?key=&lt;OmvRestClientParams.authenticationCode&gt;</code>Format definition: <code>&lt;http&#124;https&gt;://&lt;baseURL&gt;/map/&lt;versionNumber&gt;/tile/&lt;layer&gt;/&lt;style&gt;/&lt;zoom&gt;/&lt;X&gt;/&lt;Y&gt;.&lt;format&gt;?key=&lt;apiKey&gt;[&amp;view=&lt;view&gt;][&amp;language=&lt;language&gt;]</code>Sample URL: <code>http://api.tomtom.com/map/1/tile/basic/main/0/0/0.pbf?key=&lt;apiKey&gt;</code>Default authentication method used: \[\[AuthenticationTypeTomTomV1\]\]. |
|  XYZJson | <code>3</code> | Use the REST API format of XYZ Vector Tile API in JSON format.<!-- -->Usage: <code>&lt;OmvRestClientParams.baseUrl&gt;/tiles/omsbase/256/&lt;zoom&gt;/&lt;X&gt;/&lt;Y&gt;.mvt?access_token=&lt;OmvRestClientParams.authenticationCode&gt;</code>Format definition: <code>http&#124;s://&lt;base-url&gt;/tiles/{layers}/{z}/{x}/{y}/{format}?access_token={access_token}</code>Sample URL: <code>https://xyz.api.here.com/tiles/osmbase/256/all/16/19293/24641.json?access_token=your-xyz-api-key</code>Default authentication method used: \[\[AuthenticationTypeAccessToken\]\]. |
|  XYZMVT | <code>2</code> | Use the REST API format of XYZ Vector Tile API in MVT format.<!-- -->Usage: <code>&lt;OmvRestClientParams.baseUrl&gt;/tiles/omsbase/256/&lt;zoom&gt;/&lt;X&gt;/&lt;Y&gt;.mvt?access_token=&lt;OmvRestClientParams.authenticationCode&gt;</code>Format definition: <code>http&#124;s://&lt;base-url&gt;/tiles/{layers}/{z}/{x}/{y}/{format}?access_token={access_token}</code>Sample URL: <code>https://xyz.api.here.com/tiles/osmbase/256/all/16/19293/24641.mvt?access_token=your-xyz-access-token</code>Default authentication method used: \[\[AuthenticationTypeAccessToken\]\]. |
|  XYZOMV | <code>4</code> | Use the REST API format of XYZ Vector Tile API in OMV format.<!-- -->Usage: <code>&lt;OmvRestClientParams.baseUrl&gt;/tiles/herebase.02/&lt;zoom&gt;/&lt;X&gt;/&lt;Y&gt;/omv?access_token=&lt;OmvRestClientParams.authenticationCode&gt;</code>Format definition: <code>http&#124;s://&lt;base-url&gt;/tiles/herebase.02/{z}/{x}/{y}/{format}?access_token={access_token}</code>Sample URL: <code>https://xyz.api.here.com/tiles/herebase.02/14/2649/6338/omv?access_token=your-xyz-access-token</code>Default authentication method used: \[\[AuthenticationTypeAccessToken\]\]. |
|  XYZSpace | <code>6</code> | Use the REST API format of XYZ Space Vector Tile API in OMV format.<!-- -->Usage: <code>&lt;OmvRestClientParams.baseUrl&gt;/hub/spaces/&lt;space-id&gt;/tile/web/&lt;zoom&gt;_&lt;X&gt;_&lt;Y&gt;.mvt?access_token=&lt;OmvRestClientParams.authenticationCode&gt;</code>Format definition: <code>http&#124;s://&lt;base-url&gt;/hub/spaces/{spaceId}/tile/web/{z}_{x}_{y}.mvt?access_token={access_token}</code>Sample URL: <code>https://xyz.api.here.com/hub/spaces/your-space-id/tile/web/{z}_{x}_{y}.mvt?access_token=your-access-token</code>Default authentication method used: \[\[AuthenticationTypeAccessToken\]\]. |
