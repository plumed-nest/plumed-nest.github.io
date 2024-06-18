**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/tetra_pept/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1215-453:06655] *** Process received signal ***
[fv-az1215-453:06655] Signal: Aborted (6)
[fv-az1215-453:06655] Signal code:  (-6)
[fv-az1215-453:06655] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9d6e842520]
[fv-az1215-453:06655] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f9d6e8969fc]
[fv-az1215-453:06655] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9d6e842476]
[fv-az1215-453:06655] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f9d6e8287f3]
[fv-az1215-453:06655] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f9d6eca2b9e]
[fv-az1215-453:06655] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f9d6ecae20c]
[fv-az1215-453:06655] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f9d6ecae277]
[fv-az1215-453:06655] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f9d6ecae52b]
[fv-az1215-453:06655] [ 8] plumed_master(+0x14274)[0x55c6546f7274]
[fv-az1215-453:06655] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9d6e829d90]
[fv-az1215-453:06655] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9d6e829e40]
[fv-az1215-453:06655] [11] plumed_master(+0x14ed5)[0x55c6546f7ed5]
[fv-az1215-453:06655] *** End of error message ***
</pre>
{% endraw %}
