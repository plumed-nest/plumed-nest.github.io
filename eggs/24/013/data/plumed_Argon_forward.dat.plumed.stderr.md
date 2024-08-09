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
[fv-az1490-855:04011] *** Process received signal ***
[fv-az1490-855:04011] Signal: Aborted (6)
[fv-az1490-855:04011] Signal code:  (-6)
[fv-az1490-855:04011] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff3ee242520]
[fv-az1490-855:04011] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff3ee2969fc]
[fv-az1490-855:04011] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff3ee242476]
[fv-az1490-855:04011] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff3ee2287f3]
[fv-az1490-855:04011] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7ff3ee6a2b9e]
[fv-az1490-855:04011] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7ff3ee6ae20c]
[fv-az1490-855:04011] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7ff3ee6ae277]
[fv-az1490-855:04011] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff3ee6ae52b]
[fv-az1490-855:04011] [ 8] plumed(+0x12f48)[0x55b4dfc50f48]
[fv-az1490-855:04011] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff3ee229d90]
[fv-az1490-855:04011] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff3ee229e40]
[fv-az1490-855:04011] [11] plumed(+0x131e5)[0x55b4dfc511e5]
[fv-az1490-855:04011] *** End of error message ***
</pre>
{% endraw %}
