**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/3_BAD_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[fv-az1429-284:05010] *** Process received signal ***
[fv-az1429-284:05010] Signal: Aborted (6)
[fv-az1429-284:05010] Signal code:  (-6)
[fv-az1429-284:05010] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f04ae842520]
[fv-az1429-284:05010] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f04ae8969fc]
[fv-az1429-284:05010] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f04ae842476]
[fv-az1429-284:05010] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f04ae8287f3]
[fv-az1429-284:05010] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f04aeca2b9e]
[fv-az1429-284:05010] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f04aecae20c]
[fv-az1429-284:05010] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f04aecae277]
[fv-az1429-284:05010] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f04aecae52b]
[fv-az1429-284:05010] [ 8] plumed(+0x14254)[0x55c7bbc85254]
[fv-az1429-284:05010] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f04ae829d90]
[fv-az1429-284:05010] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f04ae829e40]
[fv-az1429-284:05010] [11] plumed(+0x14eb5)[0x55c7bbc85eb5]
[fv-az1429-284:05010] *** End of error message ***
</pre>
{% endraw %}