**Project ID:** [plumID:24.015]({{ '/' | absolute_url }}eggs/24/015/)  
Stderr for source:  qmmm/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PATHCV" is not known.
[fv-az775-215:03891] *** Process received signal ***
[fv-az775-215:03891] Signal: Aborted (6)
[fv-az775-215:03891] Signal code:  (-6)
[fv-az775-215:03891] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6deac42520]
[fv-az775-215:03891] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f6deac969fc]
[fv-az775-215:03891] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6deac42476]
[fv-az775-215:03891] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f6deac287f3]
[fv-az775-215:03891] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f6deb0a2b9e]
[fv-az775-215:03891] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f6deb0ae20c]
[fv-az775-215:03891] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f6deb0ae277]
[fv-az775-215:03891] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f6deb0ae52b]
[fv-az775-215:03891] [ 8] plumed(+0x14254)[0x5627cf838254]
[fv-az775-215:03891] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6deac29d90]
[fv-az775-215:03891] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6deac29e40]
[fv-az775-215:03891] [11] plumed(+0x14eb5)[0x5627cf838eb5]
[fv-az775-215:03891] *** End of error message ***
</pre>
{% endraw %}
