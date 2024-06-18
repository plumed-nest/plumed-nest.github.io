**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1272-851:09376] *** Process received signal ***
[fv-az1272-851:09376] Signal: Aborted (6)
[fv-az1272-851:09376] Signal code:  (-6)
[fv-az1272-851:09376] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe0b9842520]
[fv-az1272-851:09376] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe0b98969fc]
[fv-az1272-851:09376] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe0b9842476]
[fv-az1272-851:09376] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe0b98287f3]
[fv-az1272-851:09376] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe0b9ca2b9e]
[fv-az1272-851:09376] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe0b9cae20c]
[fv-az1272-851:09376] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe0b9cae277]
[fv-az1272-851:09376] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe0b9cae52b]
[fv-az1272-851:09376] [ 8] plumed_master(+0x14274)[0x5613ee63a274]
[fv-az1272-851:09376] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe0b9829d90]
[fv-az1272-851:09376] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe0b9829e40]
[fv-az1272-851:09376] [11] plumed_master(+0x14ed5)[0x5613ee63aed5]
[fv-az1272-851:09376] *** End of error message ***
</pre>
{% endraw %}
