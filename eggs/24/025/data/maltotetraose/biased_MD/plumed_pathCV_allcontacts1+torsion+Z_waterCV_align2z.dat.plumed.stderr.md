**Project ID:** [plumID:24.025]({{ '/' | absolute_url }}eggs/24/025/)  
Stderr for source:  maltotetraose/biased_MD/plumed_pathCV_allcontacts1+torsion+Z_waterCV_align2z.dat   
Download: [zipped raw stdout](plumed_pathCV_allcontacts1+torsion+Z_waterCV_align2z.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pathCV_allcontacts1+torsion+Z_waterCV_align2z.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[runnervmccnms:27261] *** Process received signal ***
[runnervmccnms:27261] Signal: Segmentation fault (11)
[runnervmccnms:27261] Signal code:  (128)
[runnervmccnms:27261] Failing at address: (nil)
[runnervmccnms:27261] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47e10) [0x7b2e54a47e10]
[runnervmccnms:27261] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x7b2e462b3fc7]
[runnervmccnms:27261] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x7b2e462c38d8]
[runnervmccnms:27261] [ 3] /home/runner/opt/libtorch/lib/libc10.so(_ZN3c106DeviceC2ERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xae2) [0x7b2e42a1f5a2]
[runnervmccnms:27261] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0xfa8) [0x7b2e4651a708]
[runnervmccnms:27261] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x7b2e4651ba98]
[runnervmccnms:27261] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x7b2e4651bcbe]
[runnervmccnms:27261] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x7b2e464c54f1]
[runnervmccnms:27261] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x7b2e464c5790]
[runnervmccnms:27261] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8302) [0x7b2e464c8302]
[runnervmccnms:27261] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x7b2e464c8cd4]
[runnervmccnms:27261] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x7b2e464cba85]
[runnervmccnms:27261] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x7b2e464cbb8f]
[runnervmccnms:27261] [13] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4c2) [0x7b2e5651a9c2]
[runnervmccnms:27261] [14] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x7b2e5651edfc]
[runnervmccnms:27261] [15] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x38e) [0x7b2e55e6177e]
[runnervmccnms:27261] [16] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x1ce) [0x7b2e55efd4de]
[runnervmccnms:27261] [17] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x7b2e55efde2e]
[runnervmccnms:27261] [18] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x9e) [0x7b2e55f0198e]
[runnervmccnms:27261] [19] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain4initEv+0x14a7) [0x7b2e55f02ff7]
[runnervmccnms:27261] [20] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x1d35) [0x7b2e55f053a5]
[runnervmccnms:27261] [21] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD7cltools6DriverIdE4mainEP8_IO_FILES4_RNS_12CommunicatorE+0x3193) [0x7b2e55b905d3]
[runnervmccnms:27261] [22] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10CLToolMain3runEiPPcP8_IO_FILES4_RNS_12CommunicatorE+0x1436) [0x7b2e55ead9c6]
[runnervmccnms:27261] [23] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10CLToolMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0xb35) [0x7b2e55eb0855]
[runnervmccnms:27261] [24] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x122c) [0x7b2e55f0489c]
[runnervmccnms:27261] [25] /home/runner/opt/lib/libplumedKernel.so(+0x90ceda) [0x7b2e55f0ceda]
[runnervmccnms:27261] [26] plumed(+0x10f8e) [0x5ee7077b9f8e]
[runnervmccnms:27261] [27] plumed(+0xb0d9) [0x5ee7077b40d9]
[runnervmccnms:27261] [28] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x2a8c1) [0x7b2e54a2a8c1]
[runnervmccnms:27261] [29] /usr/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x88) [0x7b2e54a2a9d8]
[runnervmccnms:27261] *** End of error message ***
</pre>
{% endraw %}
