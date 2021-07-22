**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
../../code/Contacts.cpp: In constructor ‘PLMD::colvar::Contacts::Contacts(const PLMD::ActionOptions&)’:
../../code/Contacts.cpp:93:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
   93 |   for(unsigned int i=0; i<num_atomsa; i++)
      |                         ~^~~~~~~~~~~
../../code/Contacts.cpp:99:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
   99 |   for(unsigned int i=0; i<num_atomsb; i++)
      |                         ~^~~~~~~~~~~
../../code/Contacts.cpp:124:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
  124 |   for(unsigned int i=0;i<num_atomsa;++i){
      |                        ~^~~~~~~~~~~
../../code/Contacts.cpp:129:25: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
  129 |   for(unsigned int i=0;i<num_atomsb;++i){
      |                        ~^~~~~~~~~~~
</pre>
{% endraw %}
