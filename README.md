## my roblox fflags config
- no mean to exploit nor doing anything here, this are my fflags that works best for my machine.
- This config repo is for the app Sober (Roblox runtime on Linux using Android translation layer and they DO NOT have any affiliation with Roblox).
- For W*ndows, take the middle part.

## About
- It sets fps to 63 ~> 64 to display smoothly on standard 60hz monitors.
> [!NOTE]
> __TIP: ALWAYS SET THE FPS CAP HIGHER THAN YOUR MONITOR REFRESH RATE. Ex: IF YOUR MONITOR REFRESH RATE IS 75hz, SET THE FPS CAP TO 77hz SO YOU CAN GET THE SMOOTHEST EXPERIENCE__
  - `"DFIntTaskSchedulerTargetFps": "63",`

- Also displays your fps (cool feature)
  - `"FFlagDebugDisplayFPS": true,`

- Launch games quick (I have no idea how this works)
  - `"FFlagEnableQuickGameLaunch": true,`

- It will reduce the graphics to the lowest and some optimisation.
  - `"FIntDebugForceMSAASamples": "0",`
  - `"DFFlagDebugPauseVoxelizer": true,`
  - `"DFFlagDebugRenderForceTechnologyVoxel": true,`
  - `"DFFlagTextureQualityOverrideEnabled": true,`
  - `"DFIntPerformanceControlTextureQualityBestUtility": "1",`
  - `"DFIntTextureQualityOverride": "0",`
  - `"FFlagDebugDisableOTAMaterialTexture": true,`
  - `"FFlagDebugRenderingSetDeterministic": true,`
  - `"FFlagDisablePostFx": true,`


- It improves internet connection via optimizing the size of packets (I have no idea what im saying here lol).
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
    
- Use threading for better fps.
  - `"FFlagDebugCheckRenderThreading": true,`
    
- It uses the Vulkan Graphics API to function.
  - `"FFlagDebugGraphicsPreferVulkan": true, `
  - `"FFlagRenderVulkanFixMinimizeWindow": true,`
  - `"FFlagDebugGraphicsDisableDirect3D11": true,`

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
