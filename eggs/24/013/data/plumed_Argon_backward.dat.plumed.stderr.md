**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action COORDINATIONNUMBER with label coord : keyword MORE_THAN could not be read correctly
[fv-az1490-855:03978] *** Process received signal ***
[fv-az1490-855:03978] Signal: Aborted (6)
[fv-az1490-855:03978] Signal code:  (-6)
[fv-az1490-855:03978] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fb585442520]
[fv-az1490-855:03978] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fb5854969fc]
[fv-az1490-855:03978] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fb585442476]
[fv-az1490-855:03978] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fb5854287f3]
[fv-az1490-855:03978] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fb5858a2b9e]
[fv-az1490-855:03978] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fb5858ae20c]
[fv-az1490-855:03978] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fb5858ae277]
[fv-az1490-855:03978] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fb5858ae52b]
[fv-az1490-855:03978] [ 8] plumed(+0x12f48)[0x56321ba62f48]
[fv-az1490-855:03978] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fb585429d90]
[fv-az1490-855:03978] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fb585429e40]
[fv-az1490-855:03978] [11] plumed(+0x131e5)[0x56321ba631e5]
[fv-az1490-855:03978] *** End of error message ***
</pre>
{% endraw %}
