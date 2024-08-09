**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action DISTANCE with label @0 : Number of specified atoms should be 2
[fv-az530-623:09252] *** Process received signal ***
[fv-az530-623:09252] Signal: Aborted (6)
[fv-az530-623:09252] Signal code:  (-6)
[fv-az530-623:09252] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fe716a42520]
[fv-az530-623:09252] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fe716a969fc]
[fv-az530-623:09252] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fe716a42476]
[fv-az530-623:09252] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fe716a287f3]
[fv-az530-623:09252] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fe716ea2b9e]
[fv-az530-623:09252] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fe716eae20c]
[fv-az530-623:09252] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fe716eae277]
[fv-az530-623:09252] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fe716eae52b]
[fv-az530-623:09252] [ 8] plumed(+0x12f48)[0x55b308ce7f48]
[fv-az530-623:09252] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fe716a29d90]
[fv-az530-623:09252] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fe716a29e40]
[fv-az530-623:09252] [11] plumed(+0x131e5)[0x55b308ce81e5]
[fv-az530-623:09252] *** End of error message ***
</pre>
{% endraw %}
