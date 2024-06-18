**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[fv-az1771-923:04114] *** Process received signal ***
[fv-az1771-923:04114] Signal: Aborted (6)
[fv-az1771-923:04114] Signal code:  (-6)
[fv-az1771-923:04114] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f012a442520]
[fv-az1771-923:04114] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f012a4969fc]
[fv-az1771-923:04114] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f012a442476]
[fv-az1771-923:04114] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f012a4287f3]
[fv-az1771-923:04114] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f012a8a2b9e]
[fv-az1771-923:04114] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f012a8ae20c]
[fv-az1771-923:04114] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f012a8ae277]
[fv-az1771-923:04114] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f012a8ae52b]
[fv-az1771-923:04114] [ 8] plumed_master(+0x14274)[0x564243cba274]
[fv-az1771-923:04114] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f012a429d90]
[fv-az1771-923:04114] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f012a429e40]
[fv-az1771-923:04114] [11] plumed_master(+0x14ed5)[0x564243cbaed5]
[fv-az1771-923:04114] *** End of error message ***
</pre>
{% endraw %}
