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
[fv-az530-623:09292] *** Process received signal ***
[fv-az530-623:09292] Signal: Aborted (6)
[fv-az530-623:09292] Signal code:  (-6)
[fv-az530-623:09292] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7505042520]
[fv-az530-623:09292] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f75050969fc]
[fv-az530-623:09292] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7505042476]
[fv-az530-623:09292] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f75050287f3]
[fv-az530-623:09292] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f75054a2b9e]
[fv-az530-623:09292] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f75054ae20c]
[fv-az530-623:09292] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f75054ae277]
[fv-az530-623:09292] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f75054ae52b]
[fv-az530-623:09292] [ 8] plumed_master(+0x14274)[0x55e3cd79d274]
[fv-az530-623:09292] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7505029d90]
[fv-az530-623:09292] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7505029e40]
[fv-az530-623:09292] [11] plumed_master(+0x14ed5)[0x55e3cd79ded5]
[fv-az530-623:09292] *** End of error message ***
</pre>
{% endraw %}
