**Project ID:** [plumID:24.025]({{ '/' | absolute_url }}eggs/24/025/)  
Stderr for source:  maltotetraose/biased_MD/plumed_pathCV_allcontacts1+torsion+Z_waterCV_align2z.dat   
Download: [zipped raw stdout](plumed_pathCV_allcontacts1+torsion+Z_waterCV_align2z.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pathCV_allcontacts1+torsion+Z_waterCV_align2z.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[runnervmccnms:27274] *** Process received signal ***
[runnervmccnms:27274] Signal: Segmentation fault (11)
[runnervmccnms:27274] Signal code:  (128)
[runnervmccnms:27274] Failing at address: (nil)
[runnervmccnms:27274] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47e10) [0x746e9ca47e10]
[runnervmccnms:27274] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x746e8e2b3fc7]
[runnervmccnms:27274] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x746e8e2c38d8]
[runnervmccnms:27274] [ 3] /home/runner/opt/libtorch/lib/libc10.so(_ZN3c106DeviceC2ERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xae2) [0x746e8aa1f5a2]
[runnervmccnms:27274] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0xfa8) [0x746e8e51a708]
[runnervmccnms:27274] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x746e8e51ba98]
[runnervmccnms:27274] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x746e8e51bcbe]
[runnervmccnms:27274] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x746e8e4c54f1]
[runnervmccnms:27274] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x746e8e4c5790]
[runnervmccnms:27274] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8302) [0x746e8e4c8302]
[runnervmccnms:27274] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x746e8e4c8cd4]
[runnervmccnms:27274] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x746e8e4cba85]
[runnervmccnms:27274] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x746e8e4cbb8f]
[runnervmccnms:27274] [13] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4ca) [0x746e9e780caa]
[runnervmccnms:27274] [14] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x746e9e78513c]
[runnervmccnms:27274] [15] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x284) [0x746e9dfc8054]
[runnervmccnms:27274] [16] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x17e) [0x746e9e095fbe]
[runnervmccnms:27274] [17] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x746e9e09656e]
[runnervmccnms:27274] [18] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xa1) [0x746e9e09d391]
[runnervmccnms:27274] [19] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain4initEv+0x1428) [0x746e9e09e978]
[runnervmccnms:27274] [20] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x2308) [0x746e9e0a12d8]
[runnervmccnms:27274] [21] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD7cltools6DriverIdE4mainEP8_IO_FILES4_RNS_12CommunicatorE+0x2e47) [0x746e9dc66247]
[runnervmccnms:27274] [22] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10CLToolMain3runEiPPcP8_IO_FILES4_RNS_12CommunicatorE+0x3127) [0x746e9e01f6c7]
[runnervmccnms:27274] [23] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10CLToolMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x772) [0x746e9e021992]
[runnervmccnms:27274] [24] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x5a0c) [0x746e9e0a49dc]
[runnervmccnms:27274] [25] /home/runner/opt/lib/libplumed_masterKernel.so(+0xaaba1a) [0x746e9e0aba1a]
[runnervmccnms:27274] [26] plumed_master(+0xaecb) [0x5782ec382ecb]
[runnervmccnms:27274] [27] plumed_master(+0x84bd) [0x5782ec3804bd]
[runnervmccnms:27274] [28] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x2a8c1) [0x746e9ca2a8c1]
[runnervmccnms:27274] [29] /usr/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x88) [0x746e9ca2a9d8]
[runnervmccnms:27274] *** End of error message ***
</pre>
{% endraw %}
