**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT1_Methanal_and_Cyanide_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1567-223:04300] *** Process received signal ***
[fv-az1567-223:04300] Signal: Aborted (6)
[fv-az1567-223:04300] Signal code:  (-6)
[fv-az1567-223:04300] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7978042520]
[fv-az1567-223:04300] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f79780969fc]
[fv-az1567-223:04300] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7978042476]
[fv-az1567-223:04300] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f79780287f3]
[fv-az1567-223:04300] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f79784a2b9e]
[fv-az1567-223:04300] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f79784ae20c]
[fv-az1567-223:04300] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f79784ae277]
[fv-az1567-223:04300] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f79784ae52b]
[fv-az1567-223:04300] [ 8] plumed_master(+0x14274)[0x55921d99b274]
[fv-az1567-223:04300] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7978029d90]
[fv-az1567-223:04300] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7978029e40]
[fv-az1567-223:04300] [11] plumed_master(+0x14ed5)[0x55921d99bed5]
[fv-az1567-223:04300] *** End of error message ***
</pre>
{% endraw %}
