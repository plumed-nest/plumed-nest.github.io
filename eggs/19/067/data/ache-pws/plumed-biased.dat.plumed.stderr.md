**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az768-943:09653] *** Process received signal ***
[fv-az768-943:09653] Signal: Aborted (6)
[fv-az768-943:09653] Signal code:  (-6)
[fv-az768-943:09653] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f41d8642520]
[fv-az768-943:09653] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f41d86969fc]
[fv-az768-943:09653] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f41d8642476]
[fv-az768-943:09653] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f41d86287f3]
[fv-az768-943:09653] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f41d8aa2b9e]
[fv-az768-943:09653] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f41d8aae20c]
[fv-az768-943:09653] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f41d8aae277]
[fv-az768-943:09653] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f41d8aae52b]
[fv-az768-943:09653] [ 8] plumed(+0x12f48)[0x563fa8e20f48]
[fv-az768-943:09653] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f41d8629d90]
[fv-az768-943:09653] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f41d8629e40]
[fv-az768-943:09653] [11] plumed(+0x131e5)[0x563fa8e211e5]
[fv-az768-943:09653] *** End of error message ***
</pre>
{% endraw %}
