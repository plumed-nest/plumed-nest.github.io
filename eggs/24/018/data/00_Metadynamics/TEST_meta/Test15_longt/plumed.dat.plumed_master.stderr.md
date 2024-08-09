**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1567-223:04111] *** Process received signal ***
[fv-az1567-223:04111] Signal: Aborted (6)
[fv-az1567-223:04111] Signal code:  (-6)
[fv-az1567-223:04111] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fddea842520]
[fv-az1567-223:04111] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fddea8969fc]
[fv-az1567-223:04111] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fddea842476]
[fv-az1567-223:04111] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fddea8287f3]
[fv-az1567-223:04111] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fddeaca2b9e]
[fv-az1567-223:04111] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fddeacae20c]
[fv-az1567-223:04111] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fddeacae277]
[fv-az1567-223:04111] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fddeacae52b]
[fv-az1567-223:04111] [ 8] plumed_master(+0x14274)[0x5600a1280274]
[fv-az1567-223:04111] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fddea829d90]
[fv-az1567-223:04111] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fddea829e40]
[fv-az1567-223:04111] [11] plumed_master(+0x14ed5)[0x5600a1280ed5]
[fv-az1567-223:04111] *** End of error message ***
</pre>
{% endraw %}
