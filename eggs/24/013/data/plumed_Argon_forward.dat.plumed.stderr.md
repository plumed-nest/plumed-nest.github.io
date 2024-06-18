**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action COORDINATIONNUMBER with label coord : keyword MORE_THAN could not be read correctly
[fv-az1771-923:04106] *** Process received signal ***
[fv-az1771-923:04106] Signal: Aborted (6)
[fv-az1771-923:04106] Signal code:  (-6)
[fv-az1771-923:04106] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9266842520]
[fv-az1771-923:04106] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f92668969fc]
[fv-az1771-923:04106] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9266842476]
[fv-az1771-923:04106] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f92668287f3]
[fv-az1771-923:04106] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f9266ca2b9e]
[fv-az1771-923:04106] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f9266cae20c]
[fv-az1771-923:04106] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f9266cae277]
[fv-az1771-923:04106] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f9266cae52b]
[fv-az1771-923:04106] [ 8] plumed(+0x12f48)[0x5559dcc42f48]
[fv-az1771-923:04106] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9266829d90]
[fv-az1771-923:04106] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9266829e40]
[fv-az1771-923:04106] [11] plumed(+0x131e5)[0x5559dcc431e5]
[fv-az1771-923:04106] *** End of error message ***
</pre>
{% endraw %}
