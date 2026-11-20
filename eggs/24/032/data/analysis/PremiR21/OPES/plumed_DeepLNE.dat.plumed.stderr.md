**Project ID:** [plumID:24.032]({{ '/' | absolute_url }}eggs/24/032/)  
Stderr for source:  analysis/PremiR21/OPES/plumed_DeepLNE.dat   
Download: [zipped raw stdout](plumed_DeepLNE.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_DeepLNE.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: using a legacy ActionRegister.h include path, please use <<#include "core/ActionRegister.h">>
In file included from /home/runner/opt/include/plumed/function/Function.h:25,
from MultiANN_tanh.IIROQo.cpp:22:
/home/runner/opt/include/plumed/function/../core/ActionWithValue.h:109:16: warning: ‘virtual void PLMD::ActionWithValue::addComponentWithDerivatives(const std::string&, const std::vector<unsigned int>&)’ was hidden [-Woverloaded-virtual=]
109 |   virtual void addComponentWithDerivatives( const std::string& name, const std::vector<unsigned>& shape=std::vector<unsigned>() );
|                ^~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/runner/opt/include/plumed/function/Function.h:45:8: note:   by ‘void PLMD::function::Function::addComponentWithDerivatives(const std::string&)’
45 |   void addComponentWithDerivatives( const std::string& name );
|        ^~~~~~~~~~~~~~~~~~~~~~~~~~~
/home/runner/opt/include/plumed/function/../core/ActionWithValue.h:92:16: warning: ‘virtual void PLMD::ActionWithValue::addValueWithDerivatives(const std::vector<unsigned int>&)’ was hidden [-Woverloaded-virtual=]
92 |   virtual void addValueWithDerivatives( const std::vector<unsigned>& shape=std::vector<unsigned>() );
|                ^~~~~~~~~~~~~~~~~~~~~~~
/home/runner/opt/include/plumed/function/Function.h:44:8: note:   by ‘void PLMD::function::Function::addValueWithDerivatives()’
44 |   void addValueWithDerivatives();
|        ^~~~~~~~~~~~~~~~~~~~~~~
</pre>
{% endraw %}
