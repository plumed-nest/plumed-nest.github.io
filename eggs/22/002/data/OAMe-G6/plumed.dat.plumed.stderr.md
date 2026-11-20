**Project ID:** [plumID:22.002]({{ '/' | absolute_url }}eggs/22/002/)  
Stderr for source:  OAMe-G6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
GAMBES_log.oahjUz.cpp: In member function ‘virtual void PLMD::bias::GAMBESL::prepare()’:
GAMBES_log.oahjUz.cpp:226:37: warning: ‘void PLMD::PlumedMain::DeprecatedAtoms::setCollectEnergy(bool) const’ is deprecated [-Wdeprecated-declarations]
226 |   plumed.getAtoms().setCollectEnergy(true);
|   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~
In file included from GAMBES_log.oahjUz.cpp:22:
/home/runner/opt/include/plumed/core/PlumedMain.h:111:10: note: declared here
111 |     void setCollectEnergy(bool b) const;
|          ^~~~~~~~~~~~~~~~
GAMBES_log.oahjUz.cpp: In member function ‘virtual void PLMD::bias::GAMBESL::calculate()’:
GAMBES_log.oahjUz.cpp:232:36: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKbT() const’ is deprecated: Use Action::getkBT() N.B. this function also reads the TEMP keyword from the input for you. [-Wdeprecated-declarations]
232 |   beta = 1/plumed.getAtoms().getKbT();
|            ~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:105:12: note: declared here
105 |     double getKbT() const ;
|            ^~~~~~
GAMBES_log.oahjUz.cpp:233:63: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKBoltzmann() const’ is deprecated: Use Action::getKBoltzmann(). [-Wdeprecated-declarations]
233 |   if(temp>0.0){ beta = 1/(temp*plumed.getAtoms().getKBoltzmann()) ; }
|                                ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:103:12: note: declared here
103 |     double getKBoltzmann() const ;
|            ^~~~~~~~~~~~~
GAMBES_log.oahjUz.cpp:252:57: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getEnergy() const’ is deprecated [-Wdeprecated-declarations]
252 |   if(iter==0){energy_offset= plumed.getAtoms().getEnergy();}
|                              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:113:12: note: declared here
113 |     double getEnergy() const ;
|            ^~~~~~~~~
GAMBES_log.oahjUz.cpp:253:44: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getEnergy() const’ is deprecated [-Wdeprecated-declarations]
253 |   double energy=plumed.getAtoms().getEnergy() - energy_offset;
|                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed/core/PlumedMain.h:113:12: note: declared here
113 |     double getEnergy() const ;
|            ^~~~~~~~~
[runnervmccnms:30364] *** Process received signal ***
[runnervmccnms:30364] Signal: Segmentation fault (11)
[runnervmccnms:30364] Signal code:  (128)
[runnervmccnms:30364] Failing at address: (nil)
[runnervmccnms:30364] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47e10) [0x743a5b847e10]
[runnervmccnms:30364] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x743a4d0b3fc7]
[runnervmccnms:30364] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x743a4d0c38d8]
[runnervmccnms:30364] [ 3] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e44b5) [0x743a4d2e44b5]
[runnervmccnms:30364] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e7dcc) [0x743a4d2e7dcc]
[runnervmccnms:30364] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e86fb) [0x743a4d2e86fb]
[runnervmccnms:30364] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8b05) [0x743a4d2e8b05]
[runnervmccnms:30364] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8bea) [0x743a4d2e8bea]
[runnervmccnms:30364] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit16ScriptTypeParser17parseTypeFromExprERKNS0_4ExprE+0xc1) [0x743a4d047551]
[runnervmccnms:30364] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit16ScriptTypeParser9parseTypeERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x1f9) [0x743a4d047819]
[runnervmccnms:30364] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit14SourceImporter8loadTypeERKN3c1013QualifiedNameE+0x4b) [0x743a4d2d9bfb]
[runnervmccnms:30364] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c587b) [0x743a4d2c587b]
[runnervmccnms:30364] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler10readGlobalERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEES9_+0x2b2) [0x743a4d315972]
[runnervmccnms:30364] [13] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0x61a) [0x743a4d319d7a]
[runnervmccnms:30364] [14] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x743a4d31ba98]
[runnervmccnms:30364] [15] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x743a4d31bcbe]
[runnervmccnms:30364] [16] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x743a4d2c54f1]
[runnervmccnms:30364] [17] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x743a4d2c5790]
[runnervmccnms:30364] [18] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8637) [0x743a4d2c8637]
[runnervmccnms:30364] [19] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x743a4d2c8cd4]
[runnervmccnms:30364] [20] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x743a4d2cba85]
[runnervmccnms:30364] [21] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x743a4d2cbb8f]
[runnervmccnms:30364] [22] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4c2) [0x743a5d31a9c2]
[runnervmccnms:30364] [23] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x743a5d31edfc]
[runnervmccnms:30364] [24] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x38e) [0x743a5cc6177e]
[runnervmccnms:30364] [25] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x1ce) [0x743a5ccfd4de]
[runnervmccnms:30364] [26] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x743a5ccfde2e]
[runnervmccnms:30364] [27] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x9e) [0x743a5cd0198e]
[runnervmccnms:30364] [28] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain4initEv+0x14a7) [0x743a5cd02ff7]
[runnervmccnms:30364] [29] /home/runner/opt/lib/libplumedKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x1d35) [0x743a5cd053a5]
[runnervmccnms:30364] *** End of error message ***
</pre>
{% endraw %}
