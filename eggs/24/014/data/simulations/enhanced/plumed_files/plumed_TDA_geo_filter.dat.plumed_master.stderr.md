**Project ID:** [plumID:24.014]({{ '/' | absolute_url }}eggs/24/014/)  
Stderr for source:  simulations/enhanced/plumed_files/plumed_TDA_geo_filter.dat   
Download: [zipped raw stdout](plumed_TDA_geo_filter.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_TDA_geo_filter.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[runnervmccnms:27541] *** Process received signal ***
[runnervmccnms:27541] Signal: Segmentation fault (11)
[runnervmccnms:27541] Signal code:  (128)
[runnervmccnms:27541] Failing at address: (nil)
[runnervmccnms:27541] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47e10) [0x72bc24047e10]
[runnervmccnms:27541] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x72bc158b3fc7]
[runnervmccnms:27541] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x72bc158c38d8]
[runnervmccnms:27541] [ 3] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e44b5) [0x72bc15ae44b5]
[runnervmccnms:27541] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e7dcc) [0x72bc15ae7dcc]
[runnervmccnms:27541] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e86fb) [0x72bc15ae86fb]
[runnervmccnms:27541] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8b05) [0x72bc15ae8b05]
[runnervmccnms:27541] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8bea) [0x72bc15ae8bea]
[runnervmccnms:27541] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit16ScriptTypeParser17parseTypeFromExprERKNS0_4ExprE+0xc1) [0x72bc15847551]
[runnervmccnms:27541] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit16ScriptTypeParser9parseTypeERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x1f9) [0x72bc15847819]
[runnervmccnms:27541] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit14SourceImporter8loadTypeERKN3c1013QualifiedNameE+0x4b) [0x72bc15ad9bfb]
[runnervmccnms:27541] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c587b) [0x72bc15ac587b]
[runnervmccnms:27541] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler10readGlobalERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEES9_+0x2b2) [0x72bc15b15972]
[runnervmccnms:27541] [13] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0x61a) [0x72bc15b19d7a]
[runnervmccnms:27541] [14] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x72bc15b1ba98]
[runnervmccnms:27541] [15] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x72bc15b1bcbe]
[runnervmccnms:27541] [16] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x72bc15ac54f1]
[runnervmccnms:27541] [17] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x72bc15ac5790]
[runnervmccnms:27541] [18] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8637) [0x72bc15ac8637]
[runnervmccnms:27541] [19] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x72bc15ac8cd4]
[runnervmccnms:27541] [20] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x72bc15acba85]
[runnervmccnms:27541] [21] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x72bc15acbb8f]
[runnervmccnms:27541] [22] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4ca) [0x72bc25d80caa]
[runnervmccnms:27541] [23] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x72bc25d8513c]
[runnervmccnms:27541] [24] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x284) [0x72bc255c8054]
[runnervmccnms:27541] [25] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x17e) [0x72bc25695fbe]
[runnervmccnms:27541] [26] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x72bc2569656e]
[runnervmccnms:27541] [27] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xa1) [0x72bc2569d391]
[runnervmccnms:27541] [28] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain4initEv+0x1428) [0x72bc2569e978]
[runnervmccnms:27541] [29] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x2308) [0x72bc256a12d8]
[runnervmccnms:27541] *** End of error message ***
</pre>
{% endraw %}
