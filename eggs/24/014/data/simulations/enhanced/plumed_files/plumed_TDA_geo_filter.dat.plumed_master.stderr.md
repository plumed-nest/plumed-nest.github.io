**Project ID:** [plumID:24.014]({{ '/' | absolute_url }}eggs/24/014/)  
Stderr for source:  simulations/enhanced/plumed_files/plumed_TDA_geo_filter.dat   
Download: [zipped raw stdout](plumed_TDA_geo_filter.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_TDA_geo_filter.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[ip-10-0-135-182:36874] *** Process received signal ***
[ip-10-0-135-182:36874] Signal: Segmentation fault (11)
[ip-10-0-135-182:36874] Signal code:  (128)
[ip-10-0-135-182:36874] Failing at address: (nil)
[ip-10-0-135-182:36874] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47dd0) [0x776476247dd0]
[ip-10-0-135-182:36874] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x776467ab3fc7]
[ip-10-0-135-182:36874] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x776467ac38d8]
[ip-10-0-135-182:36874] [ 3] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e44b5) [0x776467ce44b5]
[ip-10-0-135-182:36874] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e7dcc) [0x776467ce7dcc]
[ip-10-0-135-182:36874] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e86fb) [0x776467ce86fb]
[ip-10-0-135-182:36874] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8b05) [0x776467ce8b05]
[ip-10-0-135-182:36874] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8bea) [0x776467ce8bea]
[ip-10-0-135-182:36874] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit16ScriptTypeParser17parseTypeFromExprERKNS0_4ExprE+0xc1) [0x776467a47551]
[ip-10-0-135-182:36874] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit16ScriptTypeParser9parseTypeERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x1f9) [0x776467a47819]
[ip-10-0-135-182:36874] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit14SourceImporter8loadTypeERKN3c1013QualifiedNameE+0x4b) [0x776467cd9bfb]
[ip-10-0-135-182:36874] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c587b) [0x776467cc587b]
[ip-10-0-135-182:36874] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler10readGlobalERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEES9_+0x2b2) [0x776467d15972]
[ip-10-0-135-182:36874] [13] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0x61a) [0x776467d19d7a]
[ip-10-0-135-182:36874] [14] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x776467d1ba98]
[ip-10-0-135-182:36874] [15] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x776467d1bcbe]
[ip-10-0-135-182:36874] [16] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x776467cc54f1]
[ip-10-0-135-182:36874] [17] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x776467cc5790]
[ip-10-0-135-182:36874] [18] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8637) [0x776467cc8637]
[ip-10-0-135-182:36874] [19] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x776467cc8cd4]
[ip-10-0-135-182:36874] [20] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x776467ccba85]
[ip-10-0-135-182:36874] [21] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x776467ccbb8f]
[ip-10-0-135-182:36874] [22] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4ca) [0x776477fb35aa]
[ip-10-0-135-182:36874] [23] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x776477fb7a3c]
[ip-10-0-135-182:36874] [24] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x284) [0x7764777f0204]
[ip-10-0-135-182:36874] [25] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x17e) [0x7764778c2a6e]
[ip-10-0-135-182:36874] [26] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x7764778c302e]
[ip-10-0-135-182:36874] [27] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xa1) [0x7764778ca4d1]
[ip-10-0-135-182:36874] [28] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain4initEv+0x1928) [0x7764778cbfb8]
[ip-10-0-135-182:36874] [29] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x22a8) [0x7764778ce998]
[ip-10-0-135-182:36874] *** End of error message ***
</pre>
{% endraw %}
