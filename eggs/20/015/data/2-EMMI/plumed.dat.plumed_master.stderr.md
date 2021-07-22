**Project ID:** [plumID:20.015]({{ '/' | absolute_url }}eggs/20/015/)  
Stderr for source:  2-EMMI/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
EMMIVox.cpp: In member function ‘void PLMD::isdb::EMMIVOX::write_model_overlap(long int)’:
EMMIVox.cpp:535:17: warning: comparison of integer expressions of different signedness: ‘int’ and ‘std::vector<double>::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
  535 |   for(int i=0; i<ovmd_.size(); ++i) {
      |                ~^~~~~~~~~~~~~
EMMIVox.cpp: In member function ‘std::vector<double> PLMD::isdb::EMMIVOX::read_exp_errors(std::string)’:
EMMIVox.cpp:669:26: warning: comparison of integer expressions of different signedness: ‘unsigned int’ and ‘int’ [-Wsign-compare]
  669 |       for(unsigned i=0; i<nexp; ++i) {
      |                         ~^~~~~
EMMIVox.cpp: In member function ‘void PLMD::isdb::EMMIVOX::get_exp_data(std::string)’:
EMMIVox.cpp:800:22: warning: comparison of integer expressions of different signedness: ‘__gnu_cxx::__alloc_traits<std::allocator<int>, int>::value_type’ {aka ‘int’} and ‘std::vector<std::vector<int> >::size_type’ {aka ‘long unsigned int’} [-Wsign-compare]
  800 |     if(GMM_d_beta_[i]>=GMM_d_grps_.size()) error("Check Beta values");
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at Action.cpp:243, function void PLMD::Action::error(const string&) const
+++ message follows +++
ERROR in input to action WHOLEMOLECULES with label @3 : cannot understand the following words from the input line : REF0=5.3607,4.5911,3.1497, REF1=3.2439,3.3684,6.0308
[fv-az95-172:52161] *** Process received signal ***
[fv-az95-172:52161] Signal: Aborted (6)
[fv-az95-172:52161] Signal code:  (-6)
[fv-az95-172:52161] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7feb16f82210]
[fv-az95-172:52161] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7feb16f8218b]
[fv-az95-172:52161] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7feb16f61859]
[fv-az95-172:52161] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7feb171e9911]
[fv-az95-172:52161] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7feb171f538c]
[fv-az95-172:52161] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7feb171f53f7]
[fv-az95-172:52161] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4d)[0x7feb171f56fd]
[fv-az95-172:52161] [ 7] plumed_master(+0xf5b5)[0x56552098e5b5]
[fv-az95-172:52161] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7feb16f630b3]
[fv-az95-172:52161] [ 9] plumed_master(+0xf8be)[0x56552098e8be]
[fv-az95-172:52161] *** End of error message ***
</pre>
{% endraw %}
