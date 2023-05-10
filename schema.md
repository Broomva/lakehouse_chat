**Table 1: DATA_TRANSFER.TSDB.VW_WELL_COMPOSITE_APPA_TIMESERIES_CF_NEW** (Stores daily telemetry for all the assets in appa)

This table includes detailed metrics of all the assets in the appalachian region

- COMP_DOWN_HOURS_2: Varchar
- DOWN_CF: Boolean
- DOWN_CODE: Varchar
- DOWN_HOURS: Number
- ENERTIA_ZONEID: Varchar
- GASDAY: Timestamp_NTZ
- LINE_PRESSURE: Varchar
- METER_FUNCTION_1: Varchar
- METER_FUNCTION_2: Varchar
- METER_FUNCTION_3: Varchar
- METER_FUNCTION_4: Varchar
- METER_FUNCTION_5: Varchar
- METER_FUNCTION_6: Varchar
- METER_NUMBER_1: Varchar
- METER_NUMBER_2: Varchar
- METER_NUMBER_3: Varchar
- METER_NUMBER_4: Varchar
- METER_NUMBER_5: Varchar
- METER_NUMBER_6: Varchar
- OIL_INVENTORY: Float
- OIL_PROD: Number
- OIL_SALES: Number
- PROD_1: Varchar
- PROD_1_CF: Boolean
- PROD_2: Varchar
- PROD_2_CF: Boolean
- PROD_3: Varchar
- PROD_3_CF: Boolean
- PROD_4: Varchar
- PROD_4_CF: Boolean
- PROD_5: Varchar
- PROD_5_CF: Boolean
- PROD_6: Varchar
- PROD_6_CF: Boolean
- SITE_UID: Varchar
- TANK_CF: Boolean
- TUBING_PRESSURE: Float
- VISIT_ASSET_DATE: Timestamp_NTZ
- WATER_HAUL: Number
- WATER_INVENTORY: Float
- WATER_PROD: Number
- WELL_CF: Boolean
- WELL_NAME: Varchar


**Table 2: DATA_TRANSFER.TSDB.VW_TSDB_ZONE_MASTER** (Stores master records from all zones)

This table includes all the zones linked to the assets in the telemetry table 1

- Class: Varchar	
- DISTRICT_CODE: Varchar	
- DISTRICT_NAME: Varchar	
- DIVISION_CODE: Varchar	
- DIVISION_NAME: Varchar	
- FDC Site Code: Varchar	
- FDC Site Name: Varchar	
- Phase: Varchar	
- Prod Method: Varchar	
- REGION_CODE: Varchar	
- REGION_NAME: Varchar	
- Route Code: Varchar	
- Route Foreman: Varchar	
- Route Name: Varchar	
- Type: Varchar	
- WELL_CODE: Varchar	
- WELL_HID: Number	
- WELL_NAME: Varchar	
- ZONE_CODE: Varchar	
- ZONE_HID: Number	
- ZONE_NAME: Varchar
