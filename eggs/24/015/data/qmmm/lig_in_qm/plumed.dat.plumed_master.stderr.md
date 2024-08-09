**Project ID:** [plumID:24.015]({{ '/' | absolute_url }}eggs/24/015/)  
Stderr for source:  qmmm/lig_in_qm/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az530-623:03918] *** Process received signal ***
[fv-az530-623:03918] Signal: Aborted (6)
[fv-az530-623:03918] Signal code:  (-6)
[fv-az530-623:03918] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f8cdb242520]
[fv-az530-623:03918] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f8cdb2969fc]
[fv-az530-623:03918] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f8cdb242476]
[fv-az530-623:03918] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f8cdb2287f3]
[fv-az530-623:03918] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f8cdb6a2b9e]
[fv-az530-623:03918] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f8cdb6ae20c]
[fv-az530-623:03918] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f8cdb6ae277]
[fv-az530-623:03918] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f8cdb6ae52b]
[fv-az530-623:03918] [ 8] plumed_master(+0x14274)[0x55e489418274]
[fv-az530-623:03918] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f8cdb229d90]
[fv-az530-623:03918] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f8cdb229e40]
[fv-az530-623:03918] [11] plumed_master(+0x14ed5)[0x55e489418ed5]
[fv-az530-623:03918] *** End of error message ***
</pre>
{% endraw %}
