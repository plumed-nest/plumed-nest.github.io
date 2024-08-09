**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az693-738:08275] *** Process received signal ***
[fv-az693-738:08275] Signal: Aborted (6)
[fv-az693-738:08275] Signal code:  (-6)
[fv-az693-738:08275] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7faf31842520]
[fv-az693-738:08275] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7faf318969fc]
[fv-az693-738:08275] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7faf31842476]
[fv-az693-738:08275] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7faf318287f3]
[fv-az693-738:08275] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7faf31ca2b9e]
[fv-az693-738:08275] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7faf31cae20c]
[fv-az693-738:08275] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7faf31cae277]
[fv-az693-738:08275] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7faf31cae52b]
[fv-az693-738:08275] [ 8] plumed_master(+0x14274)[0x55c47b151274]
[fv-az693-738:08275] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7faf31829d90]
[fv-az693-738:08275] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7faf31829e40]
[fv-az693-738:08275] [11] plumed_master(+0x14ed5)[0x55c47b151ed5]
[fv-az693-738:08275] *** End of error message ***
</pre>
{% endraw %}
