**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  FFH_scripts/plumed_FFH.dat   
Download: [zipped raw stdout](plumed_FFH.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_FFH.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1016-35:07617] *** Process received signal ***
[fv-az1016-35:07617] Signal: Aborted (6)
[fv-az1016-35:07617] Signal code:  (-6)
[fv-az1016-35:07617] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fd8dea42520]
[fv-az1016-35:07617] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fd8dea969fc]
[fv-az1016-35:07617] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fd8dea42476]
[fv-az1016-35:07617] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fd8dea287f3]
[fv-az1016-35:07617] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fd8deea2b9e]
[fv-az1016-35:07617] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fd8deeae20c]
[fv-az1016-35:07617] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fd8deeae277]
[fv-az1016-35:07617] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fd8deeae52b]
[fv-az1016-35:07617] [ 8] plumed(+0x14254)[0x5635f949d254]
[fv-az1016-35:07617] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fd8dea29d90]
[fv-az1016-35:07617] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fd8dea29e40]
[fv-az1016-35:07617] [11] plumed(+0x14eb5)[0x5635f949deb5]
[fv-az1016-35:07617] *** End of error message ***
</pre>
{% endraw %}
