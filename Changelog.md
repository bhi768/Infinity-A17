# Infinity-X 17 | Xiaomi Kunzite Changelog

## Device Changes
459383f Revert "kunzite: Include MiuiCamera"
7a2820d kunzite: overlay: Force 120Hz in low brightness zone
0264a93 kunzite: Include MiuiCamera
76ce25c kunzite: sepolicy: Squashed address various AVC denials
8418b6e kunzite: sensors: Smooth auto-brightness lux and add a minimum lux floor
333b2e2 kunzite: sensors: Ignore ALS samples while the backlight ramps and smooth the lux
8607807 kunzite: sensors: Apply an empirical gain to the reported lux
b2d38fa kunzite: sepolicy: Add Mosey types to compatibility mapping
d0f8693 kunzite: sepolicy: Allow DMS to read audio properties
d3dd85f kunzite: overlay: Disable doze display state support

## Source Changes
project build/make/
16aaece build_image: get squashfs partition size from image size

project build/soong/
9191d76 java: Run local r8 in highmem_pool

project external/chromium-webview/prebuilt/arm/
170e899 Update Chromium Webview arm to 155.0.8059.39

project external/chromium-webview/prebuilt/arm64/
604ad4c Update Chromium Webview arm64 to 155.0.8059.39

project external/chromium-webview/prebuilt/x86/
2ca10d7 Update Chromium Webview x86 to 155.0.8059.39

project external/chromium-webview/prebuilt/x86_64/
de57895 Update Chromium Webview x86_64 to 155.0.8059.39

project external/setupcompat/
15f79d6 partnerconfig: Better report partner configs that are not resolved

project frameworks/base/
fdf9e5dc4 

project frameworks/opt/telephony/
2621a67 telephony: Handle scan rejection and fall back to visible cell infos

project hardware/google/pixel-sepolicy/
618c420 sepolicy: Ignore rango specific CP3A rules

project hardware/interfaces/
13fc23dae0 sensors: aidl: multihal: Add soong config to build as 32-bit

project hardware/lineage/compat/
590c948 libcodec2: Shim legacy Codec2 WorkBundle

project hardware/lineage/interfaces/
a0f3ada power-libperfmgr: Preserve session state on thread updates

project hardware/qcom-caf/sm8450-6.6/audio/primary-hal/
62783f84 audio-ar: Bump VINTF fragments to current

project hardware/qcom-caf/sm8550/audio/agm/
6651285 agm: Support sku agnostic acdb odm path

project hardware/qcom-caf/sm8550/audio/pal/
414e0111 pal: Support sku agnostic odm config path

project hardware/qcom-caf/sm8550/audio/primary-hal/
a674b233 hal/lvacfs: correctly pass input format

project manifest/
5f8b38d manifest: Initialize for v4.x

project packages/apps/Aperture/
485c98d Automatic translation import

project packages/apps/AudioFX/
2fc3a54 Automatic translation import

project packages/apps/Camelot/
cdaa570 Automatic translation import

project packages/apps/Canvas/
1a9b4ef Automatic translation import

project packages/apps/Catapult/
95352d5 Automatic translation import

project packages/apps/DeskClock/
85cde5712 Automatic translation import

project packages/apps/EuiccPolicy/
3b3c28e EuiccPolicy: Always enable EUICC packages

project packages/apps/ExactCalculator/
933974f Automatic translation import

project packages/apps/FlipFlap/
4866b33 Automatic translation import

project packages/apps/Glimpse/
89b4735 Automatic translation import

project packages/apps/InfinitySuite/
9b869db 

project packages/apps/Jelly/
64a74fb Automatic translation import

project packages/apps/Launcher3/
7f46cb1 

project packages/apps/Settings/
8d13c40 

project packages/apps/ThemePicker/
c8e013e ThemePicker: Refresh the icon preview when the accent color changes

project packages/apps/TvSettings/
cfb054d62 Automatic translation import

project packages/apps/Twelve/
fb82f3c Automatic translation import

project packages/apps/Updater/
24198a9 Updater: Replace != newupdates string with local non-translatable version

project packages/inputmethods/LatinIME/
e417ba6fa Automatic translation import

project packages/modules/Bluetooth/
79837d7 gd: hci: Allow disabling erroneous data reporting

project packages/overlays/Themes/
8d44e75 Themes: Drop NothingDotHeadline font

project packages/resources/devicesettings/
625deca Automatic translation import

project system/fs/fs_mgr/
b480de0 fs_mgr: Allow remount on a locked device

project system/memory/libmeminfo/
6e4ed65 sysmeminfo: Skip per process GPU memory usage trace if disabled in kernel

project system/update_engine/
6b25b61 update_engine: Always disable signature and downgrade checks

project vendor/crowdin/
c654f12 Automatic translation import

project vendor/extras/
c7fc1b3 Extras: Re-build GlanceableHub rro-overlays

project vendor/infinity/
95cff9c version: Bump to v4.1

project vendor/qcom/opensource/commonsys/fm/
9ec99f9 Automatic translation import
