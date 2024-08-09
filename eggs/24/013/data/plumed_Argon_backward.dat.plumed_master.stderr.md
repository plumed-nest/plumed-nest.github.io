**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[fv-az1490-855:03986] *** Process received signal ***
[fv-az1490-855:03986] Signal: Aborted (6)
[fv-az1490-855:03986] Signal code:  (-6)
[fv-az1490-855:03986] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7faf90842520]
[fv-az1490-855:03986] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7faf908969fc]
[fv-az1490-855:03986] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7faf90842476]
[fv-az1490-855:03986] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7faf908287f3]
[fv-az1490-855:03986] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7faf90ca2b9e]
[fv-az1490-855:03986] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7faf90cae20c]
[fv-az1490-855:03986] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7faf90cae277]
[fv-az1490-855:03986] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7faf90cae52b]
[fv-az1490-855:03986] [ 8] plumed_master(+0x14274)[0x55a908d88274]
[fv-az1490-855:03986] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7faf90829d90]
[fv-az1490-855:03986] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7faf90829e40]
[fv-az1490-855:03986] [11] plumed_master(+0x14ed5)[0x55a908d88ed5]
[fv-az1490-855:03986] *** End of error message ***
</pre>
{% endraw %}
