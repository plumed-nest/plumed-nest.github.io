**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[fv-az975-395:07972] *** Process received signal ***
[fv-az975-395:07972] Signal: Aborted (6)
[fv-az975-395:07972] Signal code:  (-6)
[fv-az975-395:07972] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7332c42520]
[fv-az975-395:07972] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7332c969fc]
[fv-az975-395:07972] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7332c42476]
[fv-az975-395:07972] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7332c287f3]
[fv-az975-395:07972] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f73330a2b9e]
[fv-az975-395:07972] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f73330ae20c]
[fv-az975-395:07972] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f73330ae277]
[fv-az975-395:07972] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f73330ae52b]
[fv-az975-395:07972] [ 8] plumed(+0x14254)[0x55f6411f7254]
[fv-az975-395:07972] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7332c29d90]
[fv-az975-395:07972] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7332c29e40]
[fv-az975-395:07972] [11] plumed(+0x14eb5)[0x55f6411f7eb5]
[fv-az975-395:07972] *** End of error message ***
</pre>
{% endraw %}
