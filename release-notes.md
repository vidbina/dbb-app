### Release Notes 2.1.1

Multiple signing steps
======================
There is no longer an max-inputs limit. If a transaction has more then 12 inputs, it will be split into multiple signing steps (requiring multiple times to confirm over the touchbutton)

SmartVerification simplification
================================
The app does no longer warn if the SmartVerification device (Smartphone App) is not connected.

Integer overflow bugfix
=======================
The dbb-app does no longer reject signing of transactions with a large anount that overflows int32.

