**Project ID:** [plumID:24.025]({{ '/' | absolute_url }}eggs/24/025/)  
Stderr for source:  maltohexaose/biased_MD/plumed_pathCV_allcontacts1+torsion+Z_waterCV_align2z.dat   
Download: [zipped raw stdout](plumed_pathCV_allcontacts1+torsion+Z_waterCV_align2z.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pathCV_allcontacts1+torsion+Z_waterCV_align2z.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[runnervmccnms:27232] *** Process received signal ***
[runnervmccnms:27232] Signal: Segmentation fault (11)
[runnervmccnms:27232] Signal code: Address not mapped (1)
[runnervmccnms:27232] Failing at address: 0x6479d119a490
[runnervmccnms:27232] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47e10) [0x725e45047e10]
[runnervmccnms:27232] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x725e368b3fc7]
[runnervmccnms:27232] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x725e368c38d8]
[runnervmccnms:27232] [ 3] /home/runner/opt/libtorch/lib/libc10.so(_ZN3c106DeviceC2ERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xae2) [0x725e3301f5a2]
[runnervmccnms:27232] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0xfa8) [0x725e36b1a708]
[runnervmccnms:27232] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x725e36b1ba98]
[runnervmccnms:27232] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x725e36b1bcbe]
[runnervmccnms:27232] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x725e36ac54f1]
[runnervmccnms:27232] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x725e36ac5790]
[runnervmccnms:27232] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8302) [0x725e36ac8302]
[runnervmccnms:27232] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x725e36ac8cd4]
[runnervmccnms:27232] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x725e36acba85]
[runnervmccnms:27232] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x725e36acbb8f]
[runnervmccnms:27232] [13] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4ca) [0x725e46d80caa]
[runnervmccnms:27232] [14] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x725e46d8513c]
[runnervmccnms:27232] [15] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x284) [0x725e465c8054]
[runnervmccnms:27232] [16] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x17e) [0x725e46695fbe]
[runnervmccnms:27232] [17] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x725e4669656e]
[runnervmccnms:27232] [18] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xa1) [0x725e4669d391]
[runnervmccnms:27232] [19] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain4initEv+0x1428) [0x725e4669e978]
[runnervmccnms:27232] [20] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x2308) [0x725e466a12d8]
[runnervmccnms:27232] [21] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD7cltools6DriverIdE4mainEP8_IO_FILES4_RNS_12CommunicatorE+0x2e47) [0x725e46266247]
[runnervmccnms:27232] [22] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10CLToolMain3runEiPPcP8_IO_FILES4_RNS_12CommunicatorE+0x3127) [0x725e4661f6c7]
[runnervmccnms:27232] [23] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10CLToolMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x772) [0x725e46621992]
[runnervmccnms:27232] [24] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x5a0c) [0x725e466a49dc]
[runnervmccnms:27232] [25] /home/runner/opt/lib/libplumed_masterKernel.so(+0xaaba1a) [0x725e466aba1a]
[runnervmccnms:27232] [26] plumed_master(+0xaecb) [0x6479b566eecb]
[runnervmccnms:27232] [27] plumed_master(+0x84bd) [0x6479b566c4bd]
[runnervmccnms:27232] [28] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x2a8c1) [0x725e4502a8c1]
[runnervmccnms:27232] [29] /usr/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x88) [0x725e4502a9d8]
[runnervmccnms:27232] *** End of error message ***
</pre>
{% endraw %}
