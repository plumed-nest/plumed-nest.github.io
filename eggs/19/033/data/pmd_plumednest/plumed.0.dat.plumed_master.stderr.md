**Project ID:** [plumID:19.033]({{ '/' | absolute_url }}eggs/19/033/)  
Stderr for source:  pmd_plumednest/plumed.0.dat   
(download [zipped raw stdout](plumed.0.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
PathCV.cpp: In destructor ‘virtual PLMD::function::PathCV::~PathCV()’:
PathCV.cpp:209:16: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(int i=0;i<mw_n_;++i){
                ^
PathCV.cpp: In constructor ‘PLMD::function::PathCV::PathCV(const PLMD::ActionOptions&)’:
PathCV.cpp:237:16: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(int i=0;i<mw_n_;++i){
                ^
PathCV.cpp:260:11: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
       if(i==mw_id_) ifiles[i]->close();
           ^
PathCV.cpp: In member function ‘void PLMD::function::PathCV::generatePath()’:
PathCV.cpp:484:26: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
     for(int inode=0;inode<nnodes;inode++){
                          ^
PathCV.cpp: In member function ‘void PLMD::function::PathCV::readMultipleWalkers()’:
PathCV.cpp:942:16: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(int i=0;i<mw_n_;++i){
                ^
PathCV.cpp:943:9: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
     if(i==mw_id_) continue;
         ^
</pre>
{% endraw %}
