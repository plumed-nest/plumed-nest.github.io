**Project ID:** [plumID:20.015]({{ '/' | absolute_url }}eggs/20/015/)  
Stderr for source:  EMMI-ASCT2/2-EMMI/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
EMMIVox.cpp: In member function ‘void PLMD::isdb::EMMIVOX::write_model_overlap(long int)’:
EMMIVox.cpp:535:17: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
   for(int i=0; i<ovmd_.size(); ++i) {
                 ^
EMMIVox.cpp: In member function ‘std::vector<double> PLMD::isdb::EMMIVOX::read_exp_errors(std::__cxx11::string)’:
EMMIVox.cpp:669:26: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
       for(unsigned i=0; i<nexp; ++i) {
                          ^
EMMIVox.cpp: In member function ‘void PLMD::isdb::EMMIVOX::get_exp_data(std::__cxx11::string)’:
EMMIVox.cpp:800:22: warning: comparison between signed and unsigned integer expressions [-Wsign-compare]
     if(GMM_d_beta_[i]>=GMM_d_grps_.size()) error("Check Beta values");
                      ^
</pre>
{% endraw %}
