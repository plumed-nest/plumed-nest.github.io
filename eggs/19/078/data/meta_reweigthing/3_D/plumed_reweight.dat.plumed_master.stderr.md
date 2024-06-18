**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/3_D/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1272-851:10375] *** Process received signal ***
[fv-az1272-851:10375] Signal: Aborted (6)
[fv-az1272-851:10375] Signal code:  (-6)
[fv-az1272-851:10375] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fdc40842520]
[fv-az1272-851:10375] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fdc408969fc]
[fv-az1272-851:10375] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fdc40842476]
[fv-az1272-851:10375] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fdc408287f3]
[fv-az1272-851:10375] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fdc40ca2b9e]
[fv-az1272-851:10375] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fdc40cae20c]
[fv-az1272-851:10375] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fdc40cae277]
[fv-az1272-851:10375] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fdc40cae52b]
[fv-az1272-851:10375] [ 8] plumed_master(+0x14274)[0x55f030654274]
[fv-az1272-851:10375] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fdc40829d90]
[fv-az1272-851:10375] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fdc40829e40]
[fv-az1272-851:10375] [11] plumed_master(+0x14ed5)[0x55f030654ed5]
[fv-az1272-851:10375] *** End of error message ***
</pre>
{% endraw %}
