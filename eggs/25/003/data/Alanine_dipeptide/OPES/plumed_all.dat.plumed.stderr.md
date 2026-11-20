**Project ID:** [plumID:25.003]({{ '/' | absolute_url }}eggs/25/003/)  
Stderr for source:  Alanine_dipeptide/OPES/plumed_all.dat   
Download: [zipped raw stdout](plumed_all.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_all.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[ip-10-0-130-9:26698] *** Process received signal ***
[ip-10-0-130-9:26698] Signal: Segmentation fault (11)
[ip-10-0-130-9:26698] Signal code:  (128)
[ip-10-0-130-9:26698] Failing at address: (nil)
[ip-10-0-130-9:26698] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47e10) [0x71ab80647e10]
[ip-10-0-130-9:26698] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x71ab71eb3fc7]
[ip-10-0-130-9:26698] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x71ab71ec38d8]
[ip-10-0-130-9:26698] [ 3] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e44b5) [0x71ab720e44b5]
[ip-10-0-130-9:26698] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e7dcc) [0x71ab720e7dcc]
[ip-10-0-130-9:26698] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e86fb) [0x71ab720e86fb]
[ip-10-0-130-9:26698] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8b05) [0x71ab720e8b05]
[ip-10-0-130-9:26698] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8bea) [0x71ab720e8bea]
[ip-10-0-130-9:26698] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit16ScriptTypeParser17parseTypeFromExprERKNS0_4ExprE+0xc1) [0x71ab71e47551]
[ip-10-0-130-9:26698] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit16ScriptTypeParser9parseTypeERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x1f9) [0x71ab71e47819]
[ip-10-0-130-9:26698] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit14SourceImporter8loadTypeERKN3c1013QualifiedNameE+0x4b) [0x71ab720d9bfb]
[ip-10-0-130-9:26698] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c587b) [0x71ab720c587b]
[ip-10-0-130-9:26698] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler10readGlobalERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEES9_+0x2b2) [0x71ab72115972]
[ip-10-0-130-9:26698] [13] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0x61a) [0x71ab72119d7a]
[ip-10-0-130-9:26698] [14] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x71ab7211ba98]
[ip-10-0-130-9:26698] [15] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x71ab7211bcbe]
[ip-10-0-130-9:26698] [16] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x71ab720c54f1]
[ip-10-0-130-9:26698] [17] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x71ab720c5790]
[ip-10-0-130-9:26698] [18] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8637) [0x71ab720c8637]
[ip-10-0-130-9:26698] [19] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x71ab720c8cd4]
[ip-10-0-130-9:26698] [20] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x71ab720cba85]
[ip-10-0-130-9:26698] [21] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x71ab720cbb8f]
[ip-10-0-130-9:26698] [22] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4c2) [0x71ab8211a9c2]
[ip-10-0-130-9:26698] [23] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x71ab8211edfc]
[ip-10-0-130-9:26698] [24] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x38e) [0x71ab81a6177e]
[ip-10-0-130-9:26698] [25] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x1ce) [0x71ab81afd4de]
[ip-10-0-130-9:26698] [26] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x71ab81afde2e]
[ip-10-0-130-9:26698] [27] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x9e) [0x71ab81b0198e]
[ip-10-0-130-9:26698] [28] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain4initEv+0x14a7) [0x71ab81b02ff7]
[ip-10-0-130-9:26698] [29] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x1d35) [0x71ab81b053a5]
[ip-10-0-130-9:26698] *** End of error message ***
</pre>
{% endraw %}
