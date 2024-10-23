**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_for_reference_map.dat   
Download: [zipped raw stdout](plumed_for_reference_map.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_for_reference_map.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action VSTACK with label mat : keyword ARG is compulsory for this action
[fv-az775-215:05051] *** Process received signal ***
[fv-az775-215:05051] Signal: Aborted (6)
[fv-az775-215:05051] Signal code:  (-6)
[fv-az775-215:05051] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f89ad042520]
[fv-az775-215:05051] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f89ad0969fc]
[fv-az775-215:05051] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f89ad042476]
[fv-az775-215:05051] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f89ad0287f3]
[fv-az775-215:05051] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f89ad4a2b9e]
[fv-az775-215:05051] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f89ad4ae20c]
[fv-az775-215:05051] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f89ad4ae277]
[fv-az775-215:05051] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f89ad4ae52b]
[fv-az775-215:05051] [ 8] plumed_master(+0x14254)[0x559ed1224254]
[fv-az775-215:05051] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f89ad029d90]
[fv-az775-215:05051] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f89ad029e40]
[fv-az775-215:05051] [11] plumed_master(+0x14eb5)[0x559ed1224eb5]
[fv-az775-215:05051] *** End of error message ***
</pre>
{% endraw %}
