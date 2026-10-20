# Upstream provenance

Adapted from xiaomi-haotian-devs/android_device_xiaomi_sm8750-common,
branch lineage-23.2, commit 1c858a2fae7f175cf3ec0b76dcc64aab608329a6.
Original copyright and licence notices are preserved.

Proprietary files come from HyperOS 4 China OS4.0.0.44.XPYCNXM. Boot, AVB,
partition and fstab definitions live in each device tree.

## Differences from upstream

This tree currently serves Wi-Fi tablets. Left out from the upstream phone
common tree: GPS, NFC, telephony (and the carrier and telephony overlays),
Hypsys, the under-display fingerprint sensor HAL and the shared first-stage
fstab. A phone device needs them restored, with their blobs, before it can
share this tree.
