**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  OAMe_G2/deepDA_enhanced_sampling/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[runnervmccnms:30645] *** Process received signal ***
[runnervmccnms:30645] Signal: Segmentation fault (11)
[runnervmccnms:30645] Signal code: Address not mapped (1)
[runnervmccnms:30645] Failing at address: 0x55e9a09a13f0
[runnervmccnms:30645] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47e10) [0x75d708c47e10]
[runnervmccnms:30645] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x75d6fa4b3fc7]
[runnervmccnms:30645] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x75d6fa4c38d8]
[runnervmccnms:30645] [ 3] /home/runner/opt/libtorch/lib/libc10.so(_ZN3c106DeviceC2ERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xae2) [0x75d6f6c1f5a2]
[runnervmccnms:30645] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0xfa8) [0x75d6fa71a708]
[runnervmccnms:30645] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x75d6fa71ba98]
[runnervmccnms:30645] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x75d6fa71bcbe]
[runnervmccnms:30645] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x75d6fa6c54f1]
[runnervmccnms:30645] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x75d6fa6c5790]
[runnervmccnms:30645] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8302) [0x75d6fa6c8302]
[runnervmccnms:30645] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x75d6fa6c8cd4]
[runnervmccnms:30645] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x75d6fa6cba85]
[runnervmccnms:30645] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x75d6fa6cbb8f]
[runnervmccnms:30645] [13] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4c2) [0x75d70a71a9c2]
[runnervmccnms:30645] [14] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x75d70a71edfc]
[runnervmccnms:30645] [15] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x38e) [0x75d70a06177e]
[runnervmccnms:30645] [16] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x1ce) [0x75d70a0fd4de]
[runnervmccnms:30645] [17] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x75d70a0fde2e]
[runnervmccnms:30645] [18] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x9e) [0x75d70a10198e]
[runnervmccnms:30645] [19] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain4initEv+0x14a7) [0x75d70a102ff7]
[runnervmccnms:30645] [20] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x1d35) [0x75d70a1053a5]
[runnervmccnms:30645] [21] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD7cltools6DriverIdE4mainEP8_IO_FILES4_RNS_12CommunicatorE+0x3193) [0x75d709d905d3]
[runnervmccnms:30645] [22] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10CLToolMain3runEiPPcP8_IO_FILES4_RNS_12CommunicatorE+0x1436) [0x75d70a0ad9c6]
[runnervmccnms:30645] [23] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10CLToolMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0xb35) [0x75d70a0b0855]
[runnervmccnms:30645] [24] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x122c) [0x75d70a10489c]
[runnervmccnms:30645] [25] /home/runner/opt/lib/libplumedKernel.so(+0x90ceda) [0x75d70a10ceda]
[runnervmccnms:30645] [26] plumed(+0x10f8e) [0x55e972dc7f8e]
[runnervmccnms:30645] [27] plumed(+0xb0d9) [0x55e972dc20d9]
[runnervmccnms:30645] [28] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x2a8c1) [0x75d708c2a8c1]
[runnervmccnms:30645] [29] /usr/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x88) [0x75d708c2a9d8]
[runnervmccnms:30645] *** End of error message ***
</pre>
{% endraw %}
