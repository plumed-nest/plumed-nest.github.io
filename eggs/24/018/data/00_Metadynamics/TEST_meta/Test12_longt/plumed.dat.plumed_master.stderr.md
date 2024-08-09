**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1567-223:04016] *** Process received signal ***
[fv-az1567-223:04016] Signal: Aborted (6)
[fv-az1567-223:04016] Signal code:  (-6)
[fv-az1567-223:04016] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f242ae42520]
[fv-az1567-223:04016] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f242ae969fc]
[fv-az1567-223:04016] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f242ae42476]
[fv-az1567-223:04016] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f242ae287f3]
[fv-az1567-223:04016] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f242b2a2b9e]
[fv-az1567-223:04016] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f242b2ae20c]
[fv-az1567-223:04016] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f242b2ae277]
[fv-az1567-223:04016] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f242b2ae52b]
[fv-az1567-223:04016] [ 8] plumed_master(+0x14274)[0x5651d4eee274]
[fv-az1567-223:04016] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f242ae29d90]
[fv-az1567-223:04016] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f242ae29e40]
[fv-az1567-223:04016] [11] plumed_master(+0x14ed5)[0x5651d4eeeed5]
[fv-az1567-223:04016] *** End of error message ***
</pre>
{% endraw %}
