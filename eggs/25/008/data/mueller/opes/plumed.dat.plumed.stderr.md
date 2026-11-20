**Project ID:** [plumID:25.008]({{ '/' | absolute_url }}eggs/25/008/)  
Stderr for source:  mueller/opes/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[runnervmccnms:27415] *** Process received signal ***
[runnervmccnms:27415] Signal: Segmentation fault (11)
[runnervmccnms:27415] Signal code: Address not mapped (1)
[runnervmccnms:27415] Failing at address: 0x1caac968c710c0
[runnervmccnms:27415] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47e10) [0x71233cc47e10]
[runnervmccnms:27415] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x71232e4b3fc7]
[runnervmccnms:27415] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x71232e4c38d8]
[runnervmccnms:27415] [ 3] /home/runner/opt/libtorch/lib/libc10.so(_ZN3c106DeviceC2ERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xae2) [0x71232ac1f5a2]
[runnervmccnms:27415] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0xfa8) [0x71232e71a708]
[runnervmccnms:27415] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x71232e71ba98]
[runnervmccnms:27415] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x71232e71bcbe]
[runnervmccnms:27415] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x71232e6c54f1]
[runnervmccnms:27415] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x71232e6c5790]
[runnervmccnms:27415] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8302) [0x71232e6c8302]
[runnervmccnms:27415] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x71232e6c8cd4]
[runnervmccnms:27415] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x71232e6cba85]
[runnervmccnms:27415] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x71232e6cbb8f]
[runnervmccnms:27415] [13] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4c2) [0x71233e71a9c2]
[runnervmccnms:27415] [14] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x71233e71edfc]
[runnervmccnms:27415] [15] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x38e) [0x71233e06177e]
[runnervmccnms:27415] [16] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x1ce) [0x71233e0fd4de]
[runnervmccnms:27415] [17] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x71233e0fde2e]
[runnervmccnms:27415] [18] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x9e) [0x71233e10198e]
[runnervmccnms:27415] [19] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain4initEv+0x14a7) [0x71233e102ff7]
[runnervmccnms:27415] [20] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x1d35) [0x71233e1053a5]
[runnervmccnms:27415] [21] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD7cltools6DriverIdE4mainEP8_IO_FILES4_RNS_12CommunicatorE+0x3193) [0x71233dd905d3]
[runnervmccnms:27415] [22] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10CLToolMain3runEiPPcP8_IO_FILES4_RNS_12CommunicatorE+0x1436) [0x71233e0ad9c6]
[runnervmccnms:27415] [23] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10CLToolMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0xb35) [0x71233e0b0855]
[runnervmccnms:27415] [24] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x122c) [0x71233e10489c]
[runnervmccnms:27415] [25] /home/runner/opt/lib/libplumedKernel.so(+0x90ceda) [0x71233e10ceda]
[runnervmccnms:27415] [26] plumed(+0x10f8e) [0x61f9d8555f8e]
[runnervmccnms:27415] [27] plumed(+0xb0d9) [0x61f9d85500d9]
[runnervmccnms:27415] [28] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x2a8c1) [0x71233cc2a8c1]
[runnervmccnms:27415] [29] /usr/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x88) [0x71233cc2a9d8]
[runnervmccnms:27415] *** End of error message ***
</pre>
{% endraw %}
