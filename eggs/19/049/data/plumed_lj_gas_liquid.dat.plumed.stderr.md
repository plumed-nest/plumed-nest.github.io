**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_lj_gas_liquid.dat   
Download: [zipped raw stdout](plumed_lj_gas_liquid.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_lj_gas_liquid.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action CLUSTER_PROPERTIES with label clust1 : cannot understand the following words from the input line : ARG=lq
[fv-az1433-905:72108] *** Process received signal ***
[fv-az1433-905:72108] Signal: Aborted (6)
[fv-az1433-905:72108] Signal code:  (-6)
[fv-az1433-905:72108] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9cab842520]
[fv-az1433-905:72108] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f9cab8969fc]
[fv-az1433-905:72108] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9cab842476]
[fv-az1433-905:72108] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f9cab8287f3]
[fv-az1433-905:72108] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f9cabca4f26]
[fv-az1433-905:72108] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f9cabcb6d9c]
[fv-az1433-905:72108] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f9cabcb6e07]
[fv-az1433-905:72108] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f9cabcb70bb]
[fv-az1433-905:72108] [ 8] plumed(+0x12f48)[0x5604a0372f48]
[fv-az1433-905:72108] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9cab829d90]
[fv-az1433-905:72108] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9cab829e40]
[fv-az1433-905:72108] [11] plumed(+0x131e5)[0x5604a03731e5]
[fv-az1433-905:72108] *** End of error message ***
</pre>
{% endraw %}
