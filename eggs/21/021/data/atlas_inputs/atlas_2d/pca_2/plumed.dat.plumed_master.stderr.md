**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_2d/pca_2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1446-488:06900] *** Process received signal ***
[fv-az1446-488:06900] Signal: Aborted (6)
[fv-az1446-488:06900] Signal code:  (-6)
[fv-az1446-488:06900] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0e58842520]
[fv-az1446-488:06900] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0e588969fc]
[fv-az1446-488:06900] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0e58842476]
[fv-az1446-488:06900] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0e588287f3]
[fv-az1446-488:06900] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f0e58ca2b9e]
[fv-az1446-488:06900] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f0e58cae20c]
[fv-az1446-488:06900] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f0e58cae277]
[fv-az1446-488:06900] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f0e58cae52b]
[fv-az1446-488:06900] [ 8] plumed_master(+0x14274)[0x55feedb89274]
[fv-az1446-488:06900] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0e58829d90]
[fv-az1446-488:06900] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0e58829e40]
[fv-az1446-488:06900] [11] plumed_master(+0x14ed5)[0x55feedb89ed5]
[fv-az1446-488:06900] *** End of error message ***
</pre>
{% endraw %}
