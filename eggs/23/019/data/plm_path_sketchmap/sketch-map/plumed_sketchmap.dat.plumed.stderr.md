**Project ID:** [plumID:23.019]({{ '/' | absolute_url }}eggs/23/019/)  
Stderr for source:  plm_path_sketchmap/sketch-map/plumed_sketchmap.dat   
Download: [zipped raw stdout](plumed_sketchmap.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_sketchmap.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action VSTACK with label mat : no arguments were specificed
[fv-az775-215:05105] *** Process received signal ***
[fv-az775-215:05105] Signal: Aborted (6)
[fv-az775-215:05105] Signal code:  (-6)
[fv-az775-215:05105] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f1bcc842520]
[fv-az775-215:05105] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f1bcc8969fc]
[fv-az775-215:05105] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f1bcc842476]
[fv-az775-215:05105] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f1bcc8287f3]
[fv-az775-215:05105] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f1bccca2b9e]
[fv-az775-215:05105] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f1bcccae20c]
[fv-az775-215:05105] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f1bcccae277]
[fv-az775-215:05105] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f1bcccae52b]
[fv-az775-215:05105] [ 8] plumed(+0x14254)[0x5646b0158254]
[fv-az775-215:05105] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f1bcc829d90]
[fv-az775-215:05105] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f1bcc829e40]
[fv-az775-215:05105] [11] plumed(+0x14eb5)[0x5646b0158eb5]
[fv-az775-215:05105] *** End of error message ***
</pre>
{% endraw %}
