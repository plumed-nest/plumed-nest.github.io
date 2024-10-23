**Project ID:** [plumID:22.040]({{ '/' | absolute_url }}eggs/22/040/)  
Stderr for source:  ktr-meta-wt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:700) bool PLMD::Keywords::checkArgumentType(const size_t&, const bool&) const
WARNING: type for input argument has not been specified
[fv-az975-395:04978] *** Process received signal ***
[fv-az975-395:04978] Signal: Aborted (6)
[fv-az975-395:04978] Signal code:  (-6)
[fv-az975-395:04978] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7519a42520]
[fv-az975-395:04978] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7519a969fc]
[fv-az975-395:04978] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7519a42476]
[fv-az975-395:04978] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7519a287f3]
[fv-az975-395:04978] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f7519ea2b9e]
[fv-az975-395:04978] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f7519eae20c]
[fv-az975-395:04978] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f7519eae277]
[fv-az975-395:04978] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7519eae52b]
[fv-az975-395:04978] [ 8] plumed_master(+0x14254)[0x5652f9923254]
[fv-az975-395:04978] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7519a29d90]
[fv-az975-395:04978] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7519a29e40]
[fv-az975-395:04978] [11] plumed_master(+0x14eb5)[0x5652f9923eb5]
[fv-az975-395:04978] *** End of error message ***
</pre>
{% endraw %}
