**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az693-738:04148] *** Process received signal ***
[fv-az693-738:04148] Signal: Aborted (6)
[fv-az693-738:04148] Signal code:  (-6)
[fv-az693-738:04148] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f38afa42520]
[fv-az693-738:04148] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f38afa969fc]
[fv-az693-738:04148] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f38afa42476]
[fv-az693-738:04148] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f38afa287f3]
[fv-az693-738:04148] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f38afea2b9e]
[fv-az693-738:04148] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f38afeae20c]
[fv-az693-738:04148] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f38afeae277]
[fv-az693-738:04148] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f38afeae52b]
[fv-az693-738:04148] [ 8] plumed_master(+0x14274)[0x559eaaab1274]
[fv-az693-738:04148] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f38afa29d90]
[fv-az693-738:04148] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f38afa29e40]
[fv-az693-738:04148] [11] plumed_master(+0x14ed5)[0x559eaaab1ed5]
[fv-az693-738:04148] *** End of error message ***
</pre>
{% endraw %}
