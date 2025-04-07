## my roblox fflags config
- No mean to exploit nor doing anything here, this are my fflags that works best for my machine.
- This config repo is for the app Sober (Roblox runtime on Linux using Android translation layer and they DO NOT have any affiliation with Roblox).
- For W*ndows, take the middle part.
- This config does improve fps for roblox even on low power mode or low-end machines, so make sure to check it out!

> [!NOTE]
> Make sure to change the file name from `config.json` to `ClientAppSettings.json` and move or copy it to the roblox client configuration directory/folder! __If you are using 3rd party launchers like Bloxstrap or Fishstrap then use their config directory!__

## About
- Sets fps cap to 63 ~> 64 to display smoothly on standard 60hz monitors.
    - `"DFIntTaskSchedulerTargetFps": "63",`
> [!NOTE]
> __TIP: ALWAYS SET THE FPS CAP HIGHER THAN YOUR MONITOR REFRESH RATE. Ex: IF YOUR MONITOR REFRESH RATE IS 75hz, SET THE FPS CAP TO 77 FPS SO YOU CAN GET THE SMOOTHEST EXPERIENCE__

- Displays your fps (cool feature)
  - `"FFlagDebugDisplayFPS": true,`

- Launch games quick (I have no idea how this works)
  - `"FFlagEnableQuickGameLaunch": true,`

- Disable fflags example thing
  - `"FFlagExample": false,`

- Some monitor handle stuff
  - `"DFFlagDisableDPIScale": false,` 
  - `"FFlagHandleAltEnterFullscreenManually": false,`
  - `"FIntFullscreenTitleBarTriggerDelayMillis": "3600000",`

- Remove the 2022 texture pack
  - `"FStringPartTexturePackTable2022": "",`
  - `"FStringPartTexturePackTablePre2022": "",`
  - `"FStringTerrainMaterialTable2022": "",`
  - `"FStringTerrainMaterialTablePre2022": ""`

- Reduce the graphics to the lowest and some optimisation.
  - `"FIntDebugForceMSAASamples": "0",`
  - `"DFFlagDebugPauseVoxelizer": true,`
  - `"DFFlagDebugRenderForceTechnologyVoxel": true,`
  - `"DFFlagTextureQualityOverrideEnabled": true,`
  - `"DFIntPerformanceControlTextureQualityBestUtility": "1",`
  - `"DFIntTextureQualityOverride": "0",`
  - `"FFlagDebugDisableOTAMaterialTexture": true,`
  - `"FFlagDebugRenderingSetDeterministic": true,`
  - `"FFlagDisablePostFx": true,`
  - `"FFlagGlobalWindActivated": false,`
  - `"FFlagGlobalWindRendering": false,`
  - `"FIntFRMMaxGrassDistance": 0,`
  - `"FIntFRMMinGrassDistance": 0,`
  - `"FIntRenderGrassDetailStrands": 0,`
  - `"FIntRenderGrassHeightScaler": 0,`
  - `"FIntRenderLocalLightFadeInMs": "0",`
  - `"FIntRenderLocalLightUpdatesMax": "8",`
  - `"FIntRenderLocalLightUpdatesMin": "6",`
  - `"FIntRenderShadowIntensity": 0,`
  - `"FIntTerrainArraySliceSize": "4",`

- It improves connectivity
  - `"DFIntConnectionMTUSize": 900,`
  - `"DFIntMaxFrameBufferSize": "4",`
  - `"DFIntMinimalNetworkPrediction": "0.1",`
  - `"DFIntNetworkLatencyTolerance": "1",`
  - `"DFIntNetworkPrediction": "120",`
  - `"DFIntOptimizePingThreshold": "50",`
  - `"DFIntPlayerNetworkUpdateQueueSize": "20",`
  - `"DFIntPlayerNetworkUpdateRate": "60",`
  - `"DFIntRakNetResendRttMultiple": "1",`
  - `"DFIntRaknetBandwidthPingSendEveryXSeconds": "1",`
  - `"DFIntServerPhysicsUpdateRate": "60",`
  - `"DFIntServerTickRate": "60",`
  - `"FFlagOptimizeNetwork": true,`
  - `"FFlagOptimizeNetworkRouting": true,`
  - `"FFlagOptimizeNetworkTransport": true,`
  - `"FFlagOptimizeServerTickRate": true,`
  - `"FIntRakNetResendBufferArrayLength": "128",`

- Some changes when you are disconnected
  - `"FFlagReconnectDisabled": "True",`
  - `"FStringReconnectDisabledReason": "Check yo wifi :skull:",`

- Use threading for better fps.
  - `"FFlagDebugCheckRenderThreading": true,`
  - `"FFlagRenderDebugCheckThreading2": true,`
  - `"FIntRuntimeMaxNumOfThreads": "2400",`
  - `"FIntTaskSchedulerThreadMin": "3",`

- Uses the Vulkan Graphics API to function.
  - `"FFlagDebugGraphicsPreferVulkan": true, `
  - `"FFlagRenderVulkanFixMinimizeWindow": true,`
  - `"FFlagDebugGraphicsDisableDirect3D11": true,`
  - `"FFlagGraphicsGLTextureReduction": true,`

- Some flags to handle games that crashes on launch:
  - `"DFFlagUseVisBugChecks": false,`
  - `"FFlagEnableVisBugChecks27": false,`

- No data will be collected to avoid bans from Roblox via disable telemetry (I hope so) (It is an actual flag in roblox, I do not know if this gets you banned but use it at your risk!)
  - `"FFlagDebugDisableTelemetryEphemeralCounter": true,`
  - `"FFlagDebugDisableTelemetryEphemeralStat": true,`
  - `"FFlagDebugDisableTelemetryEventIngest": true,`
  - `"FFlagDebugDisableTelemetryPoint": true,`
  - `"FFlagDebugDisableTelemetryV2Counter": true,`
  - `"FFlagDebugDisableTelemetryV2Event": true,`
  - `"FFlagDebugDisableTelemetryV2Stat": true,`


## NO HACKS OR CHEATS IN THIS CONFIG
 
have fun with it! 😊
