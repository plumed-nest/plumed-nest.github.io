**Project ID:** [plumID:24.014]({{ '/' | absolute_url }}eggs/24/014/)  
Stderr for source:  simulations/enhanced/plumed_files/plumed_TDA_geo_nofilter.dat   
Download: [zipped raw stdout](plumed_TDA_geo_nofilter.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_TDA_geo_nofilter.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[runnervmccnms:27582] *** Process received signal ***
[runnervmccnms:27582] Signal: Segmentation fault (11)
[runnervmccnms:27582] Signal code:  (128)
[runnervmccnms:27582] Failing at address: (nil)
[runnervmccnms:27582] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47e10) [0x7b5ff1047e10]
[runnervmccnms:27582] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x7b5fe28b3fc7]
[runnervmccnms:27582] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x7b5fe28c38d8]
[runnervmccnms:27582] [ 3] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e44b5) [0x7b5fe2ae44b5]
[runnervmccnms:27582] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e7dcc) [0x7b5fe2ae7dcc]
[runnervmccnms:27582] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e86fb) [0x7b5fe2ae86fb]
[runnervmccnms:27582] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8b05) [0x7b5fe2ae8b05]
[runnervmccnms:27582] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8bea) [0x7b5fe2ae8bea]
[runnervmccnms:27582] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit16ScriptTypeParser17parseTypeFromExprERKNS0_4ExprE+0xc1) [0x7b5fe2847551]
[runnervmccnms:27582] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit16ScriptTypeParser9parseTypeERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x1f9) [0x7b5fe2847819]
[runnervmccnms:27582] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit14SourceImporter8loadTypeERKN3c1013QualifiedNameE+0x4b) [0x7b5fe2ad9bfb]
[runnervmccnms:27582] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c587b) [0x7b5fe2ac587b]
[runnervmccnms:27582] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler10readGlobalERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEES9_+0x2b2) [0x7b5fe2b15972]
[runnervmccnms:27582] [13] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0x61a) [0x7b5fe2b19d7a]
[runnervmccnms:27582] [14] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x7b5fe2b1ba98]
[runnervmccnms:27582] [15] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x7b5fe2b1bcbe]
[runnervmccnms:27582] [16] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x7b5fe2ac54f1]
[runnervmccnms:27582] [17] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x7b5fe2ac5790]
[runnervmccnms:27582] [18] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8637) [0x7b5fe2ac8637]
[runnervmccnms:27582] [19] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x7b5fe2ac8cd4]
[runnervmccnms:27582] [20] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x7b5fe2acba85]
[runnervmccnms:27582] [21] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x7b5fe2acbb8f]
[runnervmccnms:27582] [22] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4ca) [0x7b5ff2d80caa]
[runnervmccnms:27582] [23] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x7b5ff2d8513c]
[runnervmccnms:27582] [24] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x284) [0x7b5ff25c8054]
[runnervmccnms:27582] [25] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x17e) [0x7b5ff2695fbe]
[runnervmccnms:27582] [26] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x7b5ff269656e]
[runnervmccnms:27582] [27] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xa1) [0x7b5ff269d391]
[runnervmccnms:27582] [28] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain4initEv+0x1428) [0x7b5ff269e978]
[runnervmccnms:27582] [29] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x2308) [0x7b5ff26a12d8]
[runnervmccnms:27582] *** End of error message ***
</pre>
{% endraw %}
