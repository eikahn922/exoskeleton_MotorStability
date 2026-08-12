# CAD Source Manifest

Four Drive archives were supplied: a focused test package, a full-exoskeleton test package, a focused final package, and a full-exoskeleton final package. All four passed ZIP integrity checks.

The archives contained 30 total entries and 20 unique SHA-256 hashes. The repository stores each unique binary once.

## Testing

| Repository file | Bytes | SHA-256 |
|---|---:|---|
| `01 - Testing/01 - Focused Strap Placement Test/OPEN - Focused Strap Placement Test.SLDASM` | 537,208 | `35d4e3bc87a6ee9095b336a908922a9a377499c9a5a1d244d038afedc3787c04` |
| `01 - Testing/01 - Focused Strap Placement Test/Assembly Components/hipBarTester_StrapAttachment.SLDPRT` | 486,854 | `565335c4dd6c3ea905b0366748baf3bc9252a2103d9f77fd7a90f145eedb594c` |
| `01 - Testing/01 - Focused Strap Placement Test/Assembly Components/strap (1).SLDPRT` | 438,954 | `8f8863d047de40e7a079ac4859f3b635877d0936f182d23ed7c4462e43467eee` |
| `01 - Testing/02 - Full Exoskeleton Test Context/OPEN - Full Exoskeleton Test Context.SLDASM` | 1,177,945 | `ef1336fbd34ffb1cc224695924d40a1390d5a4a205e020f3ae3e737d2834922a` |
| `01 - Testing/02 - Full Exoskeleton Test Context/Assembly Components/strapInterfaceTester_ASJ.SLDASM` | 570,179 | `cacd893f3ee87f9a87421c9d989114c4c939eee17a4ee27846ac31b5aea9cf54` |
| `01 - Testing/02 - Full Exoskeleton Test Context/Assembly Components/hipBarTester_StrapAttachment.SLDPRT` | 723,220 | `7fd1af9f4867bf240ede025da3c911cef5e1b8bb477822c450025a11a43586ab` |
| `01 - Testing/02 - Full Exoskeleton Test Context/Assembly Components/RobStride_STEP.SLDPRT` | 726,727 | `8155ffd143ec0ce7fc372649c1e853c0354b91ceff705515e708ca04ba779778` |
| `01 - Testing/Shared Test Component/hipBar_Tester.SLDPRT` | 476,224 | `14890db240342eab6be5ac7d3953f3bb4e742d68a479dc981b3312fa8614795e` |

## Final implementation

| Repository file | Bytes | SHA-256 |
|---|---:|---|
| `02 - Final Implementation/01 - Focused Motor Support/OPEN - Focused Final Motor Support Assembly.SLDASM` | 559,688 | `56c93d7fbe49f96899087155c9451dc7b8431fa3cf59a7a928bda360595df379` |
| `02 - Final Implementation/02 - Full Exoskeleton Context/OPEN FIRST - Final Motor Support in Full Exoskeleton.SLDASM` | 1,163,668 | `80ec6f456169766deed1784008917238e30778d9b52db4e16180629e4a20006d` |
| `02 - Final Implementation/02 - Full Exoskeleton Context/Assembly Components/finalStrapAttachment_ASM.SLDASM` | 560,066 | `1bf84013fc1684114cd0d7d1e945a6e81f30ecaa25309b682a799b9c1dd53f02` |
| `02 - Final Implementation/02 - Full Exoskeleton Context/Assembly Components/HipBarMirrorBody2.SLDPRT` | 516,636 | `2283866c9a7db26a72815a40b2edb432a824b3a246c802097965abb4601e8318` |
| `02 - Final Implementation/02 - Full Exoskeleton Context/Assembly Components/hipBar_StrapAttachmentFinal.SLDPRT` | 508,700 | `d65de3d933e341aabd6cb1252a6c187b9e7a163e150d1ed48e382d27ab993cdb` |
| `02 - Final Implementation/02 - Full Exoskeleton Context/Assembly Components/RobStride_STEP.SLDPRT` | 726,550 | `da870145952b9ea611c2ba3a7279f8448bf76b5200cca0b52728a6ae65642f58` |

## Shared unchanged components

| Repository file | Bytes | SHA-256 |
|---|---:|---|
| `03 - Shared Exoskeleton Components/FlapTop.SLDPRT` | 227,067 | `94246407e97b704de47b46f8f5bddfa4fbe765e6846b99f95e39144823432db0` |
| `03 - Shared Exoskeleton Components/Hinge.SLDPRT` | 108,185 | `60c50952a230cf5b4fa28926d4dbf39e0cf8922fcf13ea3aa8807d65d8493b54` |
| `03 - Shared Exoskeleton Components/Hip_Lever_V2.SLDPRT` | 1,156,138 | `8becf4b700c771eecbae81167dc47353fb0912a420f2fa89188eafa21ae0d6a3` |
| `03 - Shared Exoskeleton Components/RS02.step` | 820,262 | `ab1d28c8bcf9c537611d6a409cdcd739b71ff49ad8550718e2fb9a140b25479a` |
| `03 - Shared Exoskeleton Components/strap (1).SLDPRT` | 472,620 | `3b635416e6f686cf7f55fc37eb083bbf604ae02df9127193b013ff0fe0559e2f` |
| `03 - Shared Exoskeleton Components/ThighBar.SLDPRT` | 726,135 | `ff143f92a5083754d457ea45119b7c947f0d36b33492a0b85aed4143f5c92470` |

## Important same-name differences retained

- The early and updated `hipBarTester_StrapAttachment.SLDPRT` files have different hashes.
- The early and current `strap (1).SLDPRT` files have different hashes.
- The testing and final `RobStride_STEP.SLDPRT` files have different hashes.
- The standalone focused-final assembly and the focused subassembly packaged with the full final context have different hashes.

No duplicate CAD hashes remain in the repository.
