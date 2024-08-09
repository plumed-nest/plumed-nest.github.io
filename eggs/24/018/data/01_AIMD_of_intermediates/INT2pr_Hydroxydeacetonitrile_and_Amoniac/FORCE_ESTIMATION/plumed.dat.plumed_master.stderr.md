**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2pr_Hydroxydeacetonitrile_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1567-223:04433] *** Process received signal ***
[fv-az1567-223:04433] Signal: Aborted (6)
[fv-az1567-223:04433] Signal code:  (-6)
[fv-az1567-223:04433] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fbe6d642520]
[fv-az1567-223:04433] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fbe6d6969fc]
[fv-az1567-223:04433] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fbe6d642476]
[fv-az1567-223:04433] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fbe6d6287f3]
[fv-az1567-223:04433] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fbe6daa2b9e]
[fv-az1567-223:04433] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fbe6daae20c]
[fv-az1567-223:04433] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fbe6daae277]
[fv-az1567-223:04433] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fbe6daae52b]
[fv-az1567-223:04433] [ 8] plumed_master(+0x14274)[0x562572e3f274]
[fv-az1567-223:04433] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fbe6d629d90]
[fv-az1567-223:04433] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fbe6d629e40]
[fv-az1567-223:04433] [11] plumed_master(+0x14ed5)[0x562572e3fed5]
[fv-az1567-223:04433] *** End of error message ***
</pre>
{% endraw %}
