**Project ID:** [plumID:22.040]({{ '/' | absolute_url }}eggs/22/040/)  
Stderr for source:  mw-wtmeta-wt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:700) bool PLMD::Keywords::checkArgumentType(const size_t&, const bool&) const
WARNING: type for input argument has not been specified
[fv-az975-395:05040] *** Process received signal ***
[fv-az975-395:05040] Signal: Aborted (6)
[fv-az975-395:05040] Signal code:  (-6)
[fv-az975-395:05040] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f15ef042520]
[fv-az975-395:05040] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f15ef0969fc]
[fv-az975-395:05040] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f15ef042476]
[fv-az975-395:05040] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f15ef0287f3]
[fv-az975-395:05040] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f15ef4a2b9e]
[fv-az975-395:05040] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f15ef4ae20c]
[fv-az975-395:05040] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f15ef4ae277]
[fv-az975-395:05040] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f15ef4ae52b]
[fv-az975-395:05040] [ 8] plumed_master(+0x14254)[0x55a054bb3254]
[fv-az975-395:05040] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f15ef029d90]
[fv-az975-395:05040] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f15ef029e40]
[fv-az975-395:05040] [11] plumed_master(+0x14eb5)[0x55a054bb3eb5]
[fv-az975-395:05040] *** End of error message ***
</pre>
{% endraw %}
