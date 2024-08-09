**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/2_D/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az530-623:10190] *** Process received signal ***
[fv-az530-623:10190] Signal: Aborted (6)
[fv-az530-623:10190] Signal code:  (-6)
[fv-az530-623:10190] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fbc10c42520]
[fv-az530-623:10190] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fbc10c969fc]
[fv-az530-623:10190] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fbc10c42476]
[fv-az530-623:10190] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fbc10c287f3]
[fv-az530-623:10190] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fbc110a2b9e]
[fv-az530-623:10190] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fbc110ae20c]
[fv-az530-623:10190] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fbc110ae277]
[fv-az530-623:10190] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fbc110ae52b]
[fv-az530-623:10190] [ 8] plumed_master(+0x14274)[0x555809b29274]
[fv-az530-623:10190] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fbc10c29d90]
[fv-az530-623:10190] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fbc10c29e40]
[fv-az530-623:10190] [11] plumed_master(+0x14ed5)[0x555809b29ed5]
[fv-az530-623:10190] *** End of error message ***
</pre>
{% endraw %}
