**Project ID:** [plumID:21.039]({{ '/' | absolute_url }}eggs/21/039/)  
Stderr for source:  data/ala2-multi/3_opes_multi_dtica/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[runnervmccnms:29189] *** Process received signal ***
[runnervmccnms:29189] Signal: Segmentation fault (11)
[runnervmccnms:29189] Signal code: Address not mapped (1)
[runnervmccnms:29189] Failing at address: 0x647864872a80
[runnervmccnms:29189] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47e10) [0x797cf1e47e10]
[runnervmccnms:29189] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x797ce36b3fc7]
[runnervmccnms:29189] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x797ce36c38d8]
[runnervmccnms:29189] [ 3] /home/runner/opt/libtorch/lib/libc10.so(_ZN3c106DeviceC2ERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xae2) [0x797cdfe1f5a2]
[runnervmccnms:29189] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0xfa8) [0x797ce391a708]
[runnervmccnms:29189] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x797ce391ba98]
[runnervmccnms:29189] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x797ce391bcbe]
[runnervmccnms:29189] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x797ce38c54f1]
[runnervmccnms:29189] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x797ce38c5790]
[runnervmccnms:29189] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8302) [0x797ce38c8302]
[runnervmccnms:29189] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x797ce38c8cd4]
[runnervmccnms:29189] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x797ce38cba85]
[runnervmccnms:29189] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x797ce38cbb8f]
[runnervmccnms:29189] [13] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4ca) [0x797cf3b80caa]
[runnervmccnms:29189] [14] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x797cf3b8513c]
[runnervmccnms:29189] [15] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x284) [0x797cf33c8054]
[runnervmccnms:29189] [16] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x17e) [0x797cf3495fbe]
[runnervmccnms:29189] [17] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x797cf349656e]
[runnervmccnms:29189] [18] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xa1) [0x797cf349d391]
[runnervmccnms:29189] [19] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain4initEv+0x1428) [0x797cf349e978]
[runnervmccnms:29189] [20] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x2308) [0x797cf34a12d8]
[runnervmccnms:29189] [21] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD7cltools6DriverIdE4mainEP8_IO_FILES4_RNS_12CommunicatorE+0x2e47) [0x797cf3066247]
[runnervmccnms:29189] [22] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10CLToolMain3runEiPPcP8_IO_FILES4_RNS_12CommunicatorE+0x3127) [0x797cf341f6c7]
[runnervmccnms:29189] [23] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10CLToolMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x772) [0x797cf3421992]
[runnervmccnms:29189] [24] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x5a0c) [0x797cf34a49dc]
[runnervmccnms:29189] [25] /home/runner/opt/lib/libplumed_masterKernel.so(+0xaaba1a) [0x797cf34aba1a]
[runnervmccnms:29189] [26] plumed_master(+0xaecb) [0x647854fe5ecb]
[runnervmccnms:29189] [27] plumed_master(+0x84bd) [0x647854fe34bd]
[runnervmccnms:29189] [28] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x2a8c1) [0x797cf1e2a8c1]
[runnervmccnms:29189] [29] /usr/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x88) [0x797cf1e2a9d8]
[runnervmccnms:29189] *** End of error message ***
</pre>
{% endraw %}
