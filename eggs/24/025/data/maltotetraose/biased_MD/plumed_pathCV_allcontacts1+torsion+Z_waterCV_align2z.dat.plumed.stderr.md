**Project ID:** [plumID:24.025]({{ '/' | absolute_url }}eggs/24/025/)  
Stderr for source:  maltotetraose/biased_MD/plumed_pathCV_allcontacts1+torsion+Z_waterCV_align2z.dat   
Download: [zipped raw stdout](plumed_pathCV_allcontacts1+torsion+Z_waterCV_align2z.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pathCV_allcontacts1+torsion+Z_waterCV_align2z.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
[runnervm0hi8g:36941] *** Process received signal ***
[runnervm0hi8g:36941] Signal: Segmentation fault (11)
[runnervm0hi8g:36941] Signal code: Address not mapped (1)
[runnervm0hi8g:36941] Failing at address: 0x1f3b4d46a748b0
[runnervm0hi8g:36941] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47dd0) [0x7b845de47dd0]
[runnervm0hi8g:36941] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x7b844f6b3fc7]
[runnervm0hi8g:36941] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x7b844f6c38d8]
[runnervm0hi8g:36941] [ 3] /home/runner/opt/libtorch/lib/libc10.so(_ZN3c106DeviceC2ERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xae2) [0x7b844be1f5a2]
[runnervm0hi8g:36941] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0xfa8) [0x7b844f91a708]
[runnervm0hi8g:36941] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x7b844f91ba98]
[runnervm0hi8g:36941] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x7b844f91bcbe]
[runnervm0hi8g:36941] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x7b844f8c54f1]
[runnervm0hi8g:36941] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x7b844f8c5790]
[runnervm0hi8g:36941] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8302) [0x7b844f8c8302]
[runnervm0hi8g:36941] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x7b844f8c8cd4]
[runnervm0hi8g:36941] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x7b844f8cba85]
[runnervm0hi8g:36941] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x7b844f8cbb8f]
[runnervm0hi8g:36941] [13] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4c2) [0x7b845f91a9c2]
[runnervm0hi8g:36941] [14] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x7b845f91edfc]
[runnervm0hi8g:36941] [15] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x38e) [0x7b845f26177e]
[runnervm0hi8g:36941] [16] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x1ce) [0x7b845f2fd4de]
[runnervm0hi8g:36941] [17] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x7b845f2fde2e]
[runnervm0hi8g:36941] [18] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x9e) [0x7b845f30198e]
[runnervm0hi8g:36941] [19] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain4initEv+0x14a7) [0x7b845f302ff7]
[runnervm0hi8g:36941] [20] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x1d35) [0x7b845f3053a5]
[runnervm0hi8g:36941] [21] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD7cltools6DriverIdE4mainEP8_IO_FILES4_RNS_12CommunicatorE+0x3193) [0x7b845ef905d3]
[runnervm0hi8g:36941] [22] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10CLToolMain3runEiPPcP8_IO_FILES4_RNS_12CommunicatorE+0x1436) [0x7b845f2ad9c6]
[runnervm0hi8g:36941] [23] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10CLToolMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0xb35) [0x7b845f2b0855]
[runnervm0hi8g:36941] [24] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x122c) [0x7b845f30489c]
[runnervm0hi8g:36941] [25] /home/runner/opt/lib/libplumedKernel.so(+0x90ceda) [0x7b845f30ceda]
[runnervm0hi8g:36941] [26] plumed(+0x10f8e) [0x5a3555167f8e]
[runnervm0hi8g:36941] [27] plumed(+0xb0d9) [0x5a35551620d9]
[runnervm0hi8g:36941] [28] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x2a8c1) [0x7b845de2a8c1]
[runnervm0hi8g:36941] [29] /usr/lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x88) [0x7b845de2a9d8]
[runnervm0hi8g:36941] *** End of error message ***
</pre>
{% endraw %}
