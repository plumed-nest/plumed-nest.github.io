**Project ID:** [plumID:22.002]({{ '/' | absolute_url }}eggs/22/002/)  
Stderr for source:  OAH-G3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
WARNING: "core/Atoms.h" does not exist anymore in  version >=2.10, you should change your code.
GAMBES_log.Rg7kZG.cpp: In static member function ‘static void PLMD::bias::GAMBESL::registerKeywords(PLMD::Keywords&)’:
GAMBES_log.Rg7kZG.cpp:99:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
99 |   keys.addOutputComponent("_factors","default","two or more weighing factors for bias"
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
100 |                           "these quantities will named with  the gaussian number followed by "
|                           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
101 |                           "the character string _factors. These quantities tell the user the value of the factor ");
|                           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
In file included from /home/runner/opt/include/plumed_master/core/Action.h:28,
from /home/runner/opt/include/plumed_master/core/ActionWithValue.h:25,
from GAMBES_log.Rg7kZG.cpp:23:
/home/runner/opt/include/plumed_master/core/../tools/Keywords.h:279:8: note: declared here
279 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
GAMBES_log.Rg7kZG.cpp:102:26: warning: ‘void PLMD::Keywords::addOutputComponent(const std::string&, const std::string&, const std::string&)’ is deprecated: Use addOutputComponent with four argument and specify valid types for value from scalar/vector/matrix/grid [-Wdeprecated-declarations]
102 |   keys.addOutputComponent("_averages","AVERAGES","two or more the averages");
|   ~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/runner/opt/include/plumed_master/core/../tools/Keywords.h:279:8: note: declared here
279 |   void addOutputComponent( const std::string& name, const std::string& key, const std::string& descr );
|        ^~~~~~~~~~~~~~~~~~
GAMBES_log.Rg7kZG.cpp: In member function ‘virtual void PLMD::bias::GAMBESL::prepare()’:
GAMBES_log.Rg7kZG.cpp:226:37: warning: ‘void PLMD::PlumedMain::DeprecatedAtoms::setCollectEnergy(bool) const’ is deprecated [-Wdeprecated-declarations]
226 |   plumed.getAtoms().setCollectEnergy(true);
|   ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~
In file included from GAMBES_log.Rg7kZG.cpp:22:
/home/runner/opt/include/plumed_master/core/PlumedMain.h:112:10: note: declared here
112 |     void setCollectEnergy(bool b) const;
|          ^~~~~~~~~~~~~~~~
GAMBES_log.Rg7kZG.cpp: In member function ‘virtual void PLMD::bias::GAMBESL::calculate()’:
GAMBES_log.Rg7kZG.cpp:232:36: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKbT() const’ is deprecated: Use Action::getkBT() N.B. this function also reads the TEMP keyword from the input for you. [-Wdeprecated-declarations]
232 |   beta = 1/plumed.getAtoms().getKbT();
|            ~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed_master/core/PlumedMain.h:106:12: note: declared here
106 |     double getKbT() const ;
|            ^~~~~~
GAMBES_log.Rg7kZG.cpp:233:63: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getKBoltzmann() const’ is deprecated: Use Action::getKBoltzmann(). [-Wdeprecated-declarations]
233 |   if(temp>0.0){ beta = 1/(temp*plumed.getAtoms().getKBoltzmann()) ; }
|                                ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed_master/core/PlumedMain.h:104:12: note: declared here
104 |     double getKBoltzmann() const ;
|            ^~~~~~~~~~~~~
GAMBES_log.Rg7kZG.cpp:252:57: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getEnergy() const’ is deprecated [-Wdeprecated-declarations]
252 |   if(iter==0){energy_offset= plumed.getAtoms().getEnergy();}
|                              ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed_master/core/PlumedMain.h:114:12: note: declared here
114 |     double getEnergy() const ;
|            ^~~~~~~~~
GAMBES_log.Rg7kZG.cpp:253:44: warning: ‘double PLMD::PlumedMain::DeprecatedAtoms::getEnergy() const’ is deprecated [-Wdeprecated-declarations]
253 |   double energy=plumed.getAtoms().getEnergy() - energy_offset;
|                 ~~~~~~~~~~~~~~~~~~~~~~~~~~~^~
/home/runner/opt/include/plumed_master/core/PlumedMain.h:114:12: note: declared here
114 |     double getEnergy() const ;
|            ^~~~~~~~~
[runnervmccnms:29382] *** Process received signal ***
[runnervmccnms:29382] Signal: Segmentation fault (11)
[runnervmccnms:29382] Signal code:  (128)
[runnervmccnms:29382] Failing at address: (nil)
[runnervmccnms:29382] [ 0] /usr/lib/x86_64-linux-gnu/libc.so.6(+0x47e10) [0x73a476647e10]
[runnervmccnms:29382] [ 1] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail4_NFAINSt7__cxx1112regex_traitsIcEEE18_M_eliminate_dummyEv+0x47) [0x73a467eb3fc7]
[runnervmccnms:29382] [ 2] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNSt8__detail9_CompilerINSt7__cxx1112regex_traitsIcEEEC2EPKcS6_RKSt6localeNSt15regex_constants18syntax_option_typeE+0x4a8) [0x73a467ec38d8]
[runnervmccnms:29382] [ 3] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e44b5) [0x73a4680e44b5]
[runnervmccnms:29382] [ 4] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e7dcc) [0x73a4680e7dcc]
[runnervmccnms:29382] [ 5] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e86fb) [0x73a4680e86fb]
[runnervmccnms:29382] [ 6] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8b05) [0x73a4680e8b05]
[runnervmccnms:29382] [ 7] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36e8bea) [0x73a4680e8bea]
[runnervmccnms:29382] [ 8] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit16ScriptTypeParser17parseTypeFromExprERKNS0_4ExprE+0xc1) [0x73a467e47551]
[runnervmccnms:29382] [ 9] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit16ScriptTypeParser9parseTypeERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0x1f9) [0x73a467e47819]
[runnervmccnms:29382] [10] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZNK5torch3jit14SourceImporter8loadTypeERKN3c1013QualifiedNameE+0x4b) [0x73a4680d9bfb]
[runnervmccnms:29382] [11] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c587b) [0x73a4680c587b]
[runnervmccnms:29382] [12] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler10readGlobalERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEES9_+0x2b2) [0x73a468115972]
[runnervmccnms:29382] [13] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler15readInstructionEv+0x61a) [0x73a468119d7a]
[runnervmccnms:29382] [14] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler3runEv+0xa8) [0x73a46811ba98]
[runnervmccnms:29382] [15] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit9Unpickler12parse_ivalueEv+0x2e) [0x73a46811bcbe]
[runnervmccnms:29382] [16] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit21readArchiveAndTensorsERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalISt8functionIFNS9_13StrongTypePtrERKNS9_13QualifiedNameEEEEENSA_ISB_IFNS9_13intrusive_ptrINS9_6ivalue6ObjectENS9_6detail34intrusive_target_default_null_typeISL_EEEESC_NS9_6IValueEEEEENSA_INS9_6DeviceEEERN6caffe29serialize19PyTorchStreamReaderE+0x471) [0x73a4680c54f1]
[runnervmccnms:29382] [17] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c5790) [0x73a4680c5790]
[runnervmccnms:29382] [18] /home/runner/opt/libtorch/lib/libtorch_cpu.so(+0x36c8637) [0x73a4680c8637]
[runnervmccnms:29382] [19] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadESt10shared_ptrIN6caffe29serialize20ReadAdapterInterfaceEEN3c108optionalINS6_6DeviceEEERSt13unordered_mapINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESG_St4hashISG_ESt8equal_toISG_ESaISt4pairIKSG_SG_EEE+0x1a4) [0x73a4680c8cd4]
[runnervmccnms:29382] [20] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEERSt13unordered_mapIS6_S6_St4hashIS6_ESt8equal_toIS6_ESaISt4pairIS7_S6_EEE+0xc5) [0x73a4680cba85]
[runnervmccnms:29382] [21] /home/runner/opt/libtorch/lib/libtorch_cpu.so(_ZN5torch3jit4loadERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEEN3c108optionalINS9_6DeviceEEE+0x6f) [0x73a4680cbb8f]
[runnervmccnms:29382] [22] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD8function7pytorch12PytorchModelC1ERKNS_13ActionOptionsE+0x4ca) [0x73a478380caa]
[runnervmccnms:29382] [23] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD18ActionRegistrationINS_8function7pytorch12PytorchModelEE6createERKNS_13ActionOptionsE+0x2c) [0x73a47838513c]
[runnervmccnms:29382] [24] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD14ActionRegister6createERKSt6vectorIPvSaIS2_EERKNS_13ActionOptionsE+0x284) [0x73a477bc8054]
[runnervmccnms:29382] [25] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain14readInputWordsERKSt6vectorINSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEESaIS7_EERKb+0x17e) [0x73a477c95fbe]
[runnervmccnms:29382] [26] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERNS_5IFileE+0x5e) [0x73a477c9656e]
[runnervmccnms:29382] [27] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain13readInputFileERKNSt7__cxx1112basic_stringIcSt11char_traitsIcESaIcEEE+0xa1) [0x73a477c9d391]
[runnervmccnms:29382] [28] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain4initEv+0x1428) [0x73a477c9e978]
[runnervmccnms:29382] [29] /home/runner/opt/lib/libplumed_masterKernel.so(_ZN4PLMD10PlumedMain3cmdESt17basic_string_viewIcSt11char_traitsIcEERKNS_11TypesafePtrE+0x2308) [0x73a477ca12d8]
[runnervmccnms:29382] *** End of error message ***
</pre>
{% endraw %}
