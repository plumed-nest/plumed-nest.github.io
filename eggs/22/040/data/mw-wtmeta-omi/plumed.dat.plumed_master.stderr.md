**Project ID:** [plumID:22.040]({{ '/' | absolute_url }}eggs/22/040/)  
Stderr for source:  mw-wtmeta-omi/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:700) bool PLMD::Keywords::checkArgumentType(const size_t&, const bool&) const
WARNING: type for input argument has not been specified
[fv-az975-395:05010] *** Process received signal ***
[fv-az975-395:05010] Signal: Aborted (6)
[fv-az975-395:05010] Signal code:  (-6)
[fv-az975-395:05010] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fdce4042520]
[fv-az975-395:05010] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fdce40969fc]
[fv-az975-395:05010] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fdce4042476]
[fv-az975-395:05010] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fdce40287f3]
[fv-az975-395:05010] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fdce44a2b9e]
[fv-az975-395:05010] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fdce44ae20c]
[fv-az975-395:05010] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fdce44ae277]
[fv-az975-395:05010] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fdce44ae52b]
[fv-az975-395:05010] [ 8] plumed_master(+0x14254)[0x558afc4f8254]
[fv-az975-395:05010] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fdce4029d90]
[fv-az975-395:05010] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fdce4029e40]
[fv-az975-395:05010] [11] plumed_master(+0x14eb5)[0x558afc4f8eb5]
[fv-az975-395:05010] *** End of error message ***
</pre>
{% endraw %}
