**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT1_Methanal_and_Cyanide_and_Amoniac/OLD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1567-223:04269] *** Process received signal ***
[fv-az1567-223:04269] Signal: Aborted (6)
[fv-az1567-223:04269] Signal code:  (-6)
[fv-az1567-223:04269] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f138aa42520]
[fv-az1567-223:04269] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f138aa969fc]
[fv-az1567-223:04269] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f138aa42476]
[fv-az1567-223:04269] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f138aa287f3]
[fv-az1567-223:04269] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f138aea2b9e]
[fv-az1567-223:04269] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f138aeae20c]
[fv-az1567-223:04269] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f138aeae277]
[fv-az1567-223:04269] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f138aeae52b]
[fv-az1567-223:04269] [ 8] plumed_master(+0x14274)[0x55b919856274]
[fv-az1567-223:04269] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f138aa29d90]
[fv-az1567-223:04269] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f138aa29e40]
[fv-az1567-223:04269] [11] plumed_master(+0x14ed5)[0x55b919856ed5]
[fv-az1567-223:04269] *** End of error message ***
</pre>
{% endraw %}
