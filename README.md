# ddm
DepotDownloaderMod.exe -app appid -depotkeys xxx.key (-manifest-only) (-pubfile) xxx

-pubfile----------------------------get workshop manifest

-manifest-only----------------------get manifest only

-depotkeys--------------------------load the depotkey

if the depotkey is true,get the decrypted manifests

if the depotkey is false,get the Undecrypted manifests

depotkey.key:

depotid;hexkey

like:

785481;0856170e60687e3639654046517fab3060863565fca9f1df9deddaea2c1d32f4

If you generate a workshop manifest, the depotkey needs the depotkey of the main appid (all workshop manifests have one depotkey)

If you want to use a fake depotkey to generate an unencrypted list, you only need to fill in an aes256 key at random.
