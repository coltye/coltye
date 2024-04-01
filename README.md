Cars Pack By Mr.TnT.

rename this folder to: camaross

add start camaross to your server.cfg

https://www.gta5-mods.com/vehicles/chevrolet-camaro-ss-300-drag-add-on-replace-extras
 15 changes: 15 additions & 0 deletions15  
Chevrolet/Chevrolet Camaro SS 300 Drag/__resource.lua
@@ -0,0 +1,15 @@
resource_manifest_version '77731fab-63ca-442c-a67b-abc70f28dfa5'

files {
    'vehicles.meta',
    'carvariations.meta',
    'carcols.meta',
    'handling.meta',
    'vehiclelayouts.meta',
}

data_file 'HANDLING_FILE' 'handling.meta'
data_file 'VEHICLE_METADATA_FILE' 'vehicles.meta'
data_file 'CARCOLS_FILE' 'carcols.meta'
data_file 'VEHICLE_VARIATION_FILE' 'carvariations.meta'
data_file 'VEHICLE_LAYOUTS_FILE' 'vehiclelayouts.meta'
 8 changes: 8 additions & 0 deletions8  
Chevrolet/Chevrolet Camaro SS 300 Drag/caraddoncontentunlocks.meta
@@ -0,0 +1,8 @@
<?xml version="1.0" encoding="UTF-8"?>
<SContentUnlocks>
  <listOfUnlocks>

  </listOfUnlocks>
</SContentUnlocks>


 425 changes: 425 additions & 0 deletions425  
Chevrolet/Chevrolet Camaro SS 300 Drag/carcols.meta
Large diffs are not rendered by default.

 43 changes: 43 additions & 0 deletions43  
Chevrolet/Chevrolet Camaro SS 300 Drag/carvariations.meta
@@ -0,0 +1,43 @@
<?xml version="1.0" encoding="UTF-8"?>

<CVehicleModelInfoVariation>
  <variationData>
			<Item>
			<modelName>camaross</modelName>
			<colors>
				<Item>
					<indices content="char_array">
            8 
            8 
            134 
            156
          </indices>
			<liveries>
						<Item value="true" />
						<Item value="false" />
						<Item value="false" />
						<Item value="false" />
						<Item value="false" />
						<Item value="false" />
						<Item value="false" />
						<Item value="false" />
					</liveries>
				</Item>
			</colors>
      <kits>
        <kitName>0_default_modkit</kitName>
      </kits>
      <windowsWithExposedEdges />
      <plateProbabilities>
        <Probabilities>
          <Item>
            <Name>Standard White</Name>
            <Value value="100" />
          </Item>
        </Probabilities>
      </plateProbabilities>
      <lightSettings value="1" />
      <sirenSettings value="0" />
    </Item>
  </variationData>
</CVehicleModelInfoVariation>
 7 changes: 7 additions & 0 deletions7  
Chevrolet/Chevrolet Camaro SS 300 Drag/dlctext.meta
@@ -0,0 +1,7 @@
<?xml version="1.0" encoding="UTF-8"?>

<CExtraTextMetaFile>
	<hasGlobalTextFile value="true"/>
	<hasAdditionalText value="false"/>
	<isTitleUpdate value="false"/>
</CExtraTextMetaFile>
 67 changes: 67 additions & 0 deletions67  
Chevrolet/Chevrolet Camaro SS 300 Drag/handling.meta
@@ -0,0 +1,67 @@
<?xml version="1.0" encoding="UTF-8"?>

<CHandlingDataMgr>
  <HandlingData>
	<Item type="CHandlingData">
	   <handlingName>camaross</handlingName>
      <fMass value="1800.000000" />
      <fInitialDragCoeff value="1.00000" />
      <fPercentSubmerged value="85.0" />
      <vecCentreOfMassOffset x="0" y="-0.60" z="0.06" />
      <vecInertiaMultiplier x="1.0" y="1.5" z="2.0" />
      <fDriveBiasFront value="0.0" />
      <nInitialDriveGears value="4" />
      <fInitialDriveForce value="0.67500" />
      <fDriveInertia value="1.0" />
      <fClutchChangeRateScaleUpShift value="4.100000" />
      <fClutchChangeRateScaleDownShift value="3.500000" />
      <fInitialDriveMaxFlatVel value="249.900000" />
      <fBrakeForce value="4.3" />
      <fBrakeBiasFront value="0.55" />
      <fHandBrakeForce value="1.5" />
      <fSteeringLock value="48.0" />
      <fTractionCurveMax value="2.1" />
      <fTractionCurveMin value="2.2" />
      <fTractionCurveLateral value="16.0" />
      <fTractionSpringDeltaMax value="0.13" />
      <fLowSpeedTractionLossMult value="1.0" />
      <fCamberStiffnesss value="3.5" />
      <fTractionBiasFront value="0.57" />
      <fTractionLossMult value="0.0" />
      <fSuspensionForce value="1.17" />
      <fSuspensionCompDamp value="0.700000" />
      <fSuspensionReboundDamp value="0.990000" />
      <fSuspensionUpperLimit value="0.10" />
      <fSuspensionLowerLimit value="-0.12" />
      <fSuspensionRaise value="0.03000" />
      <fSuspensionBiasFront value="0.29" />
      <fAntiRollBarForce value="1.2" />
      <fAntiRollBarBiasFront value="0.5" />
      <fRollCentreHeightFront value="0.4" />
      <fRollCentreHeightRear value="0.33" />
      <fCollisionDamageMult value="2.00" />
      <fWeaponDamageMult value="1.0" />
      <fDeformationDamageMult value="2.85" />
      <fEngineDamageMult value="7.00" />
      <fPetrolTankVolume value="65.0" />
      <fOilVolume value="10.0" />
      <fSeatOffsetDistX value="0.05" />
      <fSeatOffsetDistY value="0.0" />
      <fSeatOffsetDistZ value="0.05" />
      <nMonetaryValue value="50000" />
      <strModelFlags>440010</strModelFlags>
      <strHandlingFlags>0</strHandlingFlags>
      <strDamageFlags>0</strDamageFlags>
      <AIHandling>AVERAGE</AIHandling>
      <SubHandlingData>
        <Item type="CCarHandlingData">
          <fBackEndPopUpCarImpulseMult value="0.1" />
          <fBackEndPopUpBuildingImpulseMult value="0.03" />
          <fBackEndPopUpMaxDeltaSpeed value="0.6" />
        </Item>
        <Item type="NULL" />
        <Item type="NULL" />
      </SubHandlingData>
    </Item>
  </HandlingData>
</CHandlingDataMgr>
 Binary file addedBIN +2.23 MB 
Chevrolet/Chevrolet Camaro SS 300 Drag/stream/camaross.yft
Binary file not shown.
 Binary file addedBIN +2.38 MB 
Chevrolet/Chevrolet Camaro SS 300 Drag/stream/camaross.ytd
Binary file not shown.
 Binary file addedBIN +2.23 MB 
Chevrolet/Chevrolet Camaro SS 300 Drag/stream/camaross_hi.yft
Binary file not shown.
 126 changes: 126 additions & 0 deletions126  
Chevrolet/Chevrolet Camaro SS 300 Drag/vehicles.meta
@@ -0,0 +1,126 @@
<?xml version="1.0" encoding="UTF-8"?>
<CVehicleModelInfo__InitDataList>
  <residentTxd>vehshare</residentTxd>
  <residentAnims />
  <InitDatas>
	 <Item>
      <modelName>camaross</modelName>
      <txdName>camaross</txdName>
      <handlingId>camaross</handlingId>
      <gameName>camaross</gameName>
      <vehicleMakeName>DECLASSE</vehicleMakeName>
      <expressionDictName>null</expressionDictName>
      <expressionName>null</expressionName>
      <animConvRoofDictName>null</animConvRoofDictName>
      <animConvRoofName>null</animConvRoofName>
      <animConvRoofWindowsAffected />
      <ptfxAssetName>null</ptfxAssetName>
      <audioNameHash>btype2</audioNameHash>
      <layout>LAYOUT_LOW</layout>
      <coverBoundOffsets>VIGERO_COVER_OFFSET_INFO</coverBoundOffsets>
      <explosionInfo>EXPLOSION_INFO_DEFAULT</explosionInfo>
      <scenarioLayout />
      <cameraName>DEFAULT_FOLLOW_VEHICLE_CAMERA</cameraName>
      <aimCameraName>DEFAULT_THIRD_PERSON_VEHICLE_AIM_CAMERA</aimCameraName>
      <bonnetCameraName>VEHICLE_BONNET_CAMERA_STANDARD_HIGH</bonnetCameraName>
      <povCameraName>DEFAULT_POV_CAMERA_LOOKAROUND</povCameraName>
      <FirstPersonDriveByIKOffset x="0.000000" y="-0.030000" z="0.000000" />
      <FirstPersonDriveByUnarmedIKOffset x="0.000000" y="-0.100000" z="0.000000" />
	  <FirstPersonProjectileDriveByIKOffset x="0.000000" y="0.000000" z="-0.015000" />
	  <FirstPersonProjectileDriveByPassengerIKOffset x="-0.050000" y="0.000000" z="-0.015000" />
	  <FirstPersonProjectileDriveByRearLeftIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonProjectileDriveByRearRightIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonDriveByLeftPassengerIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonDriveByRightPassengerIKOffset x="0.000000" y="-0.030000" z="0.000000" />
	  <FirstPersonDriveByRightRearPassengerIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonDriveByLeftPassengerUnarmedIKOffset x="0.000000" y="0.000000" z="0.000000" />
	  <FirstPersonDriveByRightPassengerUnarmedIKOffset x="0.000000" y="-0.100000" z="0.000000" />
	  <FirstPersonMobilePhoneOffset x="0.155000" y="0.178000" z="0.546000" />
      <FirstPersonPassengerMobilePhoneOffset x="0.136000" y="0.128000" z="0.483000" />
      <PovCameraOffset x="0.000000" y="-0.225000" z="0.550000" />
      <PovCameraVerticalAdjustmentForRollCage value="-0.035000" />
      <PovPassengerCameraOffset x="0.000000" y="-0.050000" z="0.030000" />
      <PovRearPassengerCameraOffset x="0.000000" y="0.000000" z="0.030000" />
      <vfxInfoName>VFXVEHICLEINFO_CAR_GENERIC</vfxInfoName>
      <shouldUseCinematicViewMode value="true" />
      <shouldCameraTransitionOnClimbUpDown value="false" />
      <shouldCameraIgnoreExiting value="false" />
      <AllowPretendOccupants value="true" />
      <AllowJoyriding value="true" />
      <AllowSundayDriving value="true" />
      <AllowBodyColorMapping value="true" />
      <wheelScale value="0.223700" />
      <wheelScaleRear value="0.223700" />
      <dirtLevelMin value="0.000000" />
      <dirtLevelMax value="0.700000" />
      <envEffScaleMin value="0.000000" />
      <envEffScaleMax value="1.000000" />
      <envEffScaleMin2 value="0.000000" />
      <envEffScaleMax2 value="1.000000" />
      <damageMapScale value="0.600000" />
      <damageOffsetScale value="1.000000" />
      <diffuseTint value="0x00FFFFFF" />
      <steerWheelMult value="1.000000" />
      <HDTextureDist value="5.000000" />
      <lodDistances content="float_array">
        15.000000
        30.000000
        60.000000
        120.000000
        500.000000
        500.000000
      </lodDistances>
      <minSeatHeight value="0.837" />
      <identicalModelSpawnDistance value="20" />
      <maxNumOfSameColor value="10" />
      <defaultBodyHealth value="1000.000000" />
      <pretendOccupantsScale value="1.000000" />
      <visibleSpawnDistScale value="1.000000" />
      <trackerPathWidth value="2.000000" />
      <weaponForceMult value="1.000000" />
      <frequency value="50" />
      <swankness>SWANKNESS_2</swankness>
      <maxNum value="50" />
      <flags>FLAG_HAS_LIVERY FLAG_CAN_HAVE_NEONS FLAG_AVERAGE_CAR FLAG_RECESSED_HEADLIGHT_CORONAS FLAG_RECESSED_TAILLIGHT_CORONAS FLAG_HAS_INTERIOR_EXTRAS</flags>
      <type>VEHICLE_TYPE_CAR</type>
      <plateType>VPT_BACK_PLATES</plateType>
      <dashboardType>VDT_DUKES</dashboardType>
      <vehicleClass>VC_SUPER</vehicleClass>
      <wheelType>VWT_SPORT</wheelType>
      <trailers />
      <additionalTrailers />
      <drivers />
      <extraIncludes />
      <doorsWithCollisionWhenClosed />
      <driveableDoors />
      <bumpersNeedToCollideWithMap value="false" />
      <needsRopeTexture value="false" />
      <requiredExtras />
      <rewards />
      <cinematicPartCamera>
        <Item>WHEEL_FRONT_RIGHT_CAMERA</Item>
        <Item>WHEEL_FRONT_LEFT_CAMERA</Item>
        <Item>WHEEL_REAR_RIGHT_CAMERA</Item>
        <Item>WHEEL_REAR_LEFT_CAMERA</Item>
      </cinematicPartCamera>
      <NmBraceOverrideSet />
      <buoyancySphereOffset x="0.000000" y="0.000000" z="0.000000" />
      <buoyancySphereSizeScale value="1.000000" />
      <pOverrideRagdollThreshold type="NULL" />
	  <firstPersonDrivebyData>
        <Item>STD_VIGERO_FRONT_LEFT</Item>
        <Item>STD_TORNADO_FRONT_RIGHT</Item>
      </firstPersonDrivebyData>
    </Item>
  </InitDatas>
  <txdRelationships>
    <Item>
      <parent>vehicles_sultanrs_interior</parent>
      <child>camaross</child>
    </Item>
    <Item>
      <parent>vehicles_race_interior</parent>
      <child>vehicles_camaross_interior</child>
    </Item>	
  </txdRelationships>
</CVehicleModelInfo__InitDataList>
