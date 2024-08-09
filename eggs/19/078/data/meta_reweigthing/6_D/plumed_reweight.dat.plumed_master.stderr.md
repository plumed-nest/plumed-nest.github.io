**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/6_D/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az530-623:10370] *** Process received signal ***
[fv-az530-623:10370] Signal: Aborted (6)
[fv-az530-623:10370] Signal code:  (-6)
[fv-az530-623:10370] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3b05242520]
[fv-az530-623:10370] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3b052969fc]
[fv-az530-623:10370] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3b05242476]
[fv-az530-623:10370] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3b052287f3]
[fv-az530-623:10370] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3b056a2b9e]
[fv-az530-623:10370] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3b056ae20c]
[fv-az530-623:10370] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3b056ae277]
[fv-az530-623:10370] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3b056ae52b]
[fv-az530-623:10370] [ 8] plumed_master(+0x14274)[0x55b0afd04274]
[fv-az530-623:10370] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3b05229d90]
[fv-az530-623:10370] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3b05229e40]
[fv-az530-623:10370] [11] plumed_master(+0x14ed5)[0x55b0afd04ed5]
[fv-az530-623:10370] *** End of error message ***
</pre>
{% endraw %}
