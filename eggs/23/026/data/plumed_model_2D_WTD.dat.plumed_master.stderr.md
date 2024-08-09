**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_2D_WTD.dat   
Download: [zipped raw stdout](plumed_model_2D_WTD.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_model_2D_WTD.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az693-738:04117] *** Process received signal ***
[fv-az693-738:04117] Signal: Aborted (6)
[fv-az693-738:04117] Signal code:  (-6)
[fv-az693-738:04117] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fafe6842520]
[fv-az693-738:04117] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fafe68969fc]
[fv-az693-738:04117] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fafe6842476]
[fv-az693-738:04117] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fafe68287f3]
[fv-az693-738:04117] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fafe6ca2b9e]
[fv-az693-738:04117] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fafe6cae20c]
[fv-az693-738:04117] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fafe6cae277]
[fv-az693-738:04117] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fafe6cae52b]
[fv-az693-738:04117] [ 8] plumed_master(+0x14274)[0x558fa9c5c274]
[fv-az693-738:04117] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fafe6829d90]
[fv-az693-738:04117] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fafe6829e40]
[fv-az693-738:04117] [11] plumed_master(+0x14ed5)[0x558fa9c5ced5]
[fv-az693-738:04117] *** End of error message ***
</pre>
{% endraw %}
