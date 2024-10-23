**Project ID:** [plumID:22.040]({{ '/' | absolute_url }}eggs/22/040/)  
Stderr for source:  ktr-meta-omi/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:700) bool PLMD::Keywords::checkArgumentType(const size_t&, const bool&) const
WARNING: type for input argument has not been specified
[fv-az975-395:04947] *** Process received signal ***
[fv-az975-395:04947] Signal: Aborted (6)
[fv-az975-395:04947] Signal code:  (-6)
[fv-az975-395:04947] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fef8b442520]
[fv-az975-395:04947] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fef8b4969fc]
[fv-az975-395:04947] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fef8b442476]
[fv-az975-395:04947] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fef8b4287f3]
[fv-az975-395:04947] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fef8b8a2b9e]
[fv-az975-395:04947] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fef8b8ae20c]
[fv-az975-395:04947] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fef8b8ae277]
[fv-az975-395:04947] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fef8b8ae52b]
[fv-az975-395:04947] [ 8] plumed_master(+0x14254)[0x5566c8fe4254]
[fv-az975-395:04947] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fef8b429d90]
[fv-az975-395:04947] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fef8b429e40]
[fv-az975-395:04947] [11] plumed_master(+0x14eb5)[0x5566c8fe4eb5]
[fv-az975-395:04947] *** End of error message ***
</pre>
{% endraw %}
