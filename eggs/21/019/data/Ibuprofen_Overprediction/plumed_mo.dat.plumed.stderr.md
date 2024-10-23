**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[fv-az585-767:07269] *** Process received signal ***
[fv-az585-767:07269] Signal: Aborted (6)
[fv-az585-767:07269] Signal code:  (-6)
[fv-az585-767:07269] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f31de242520]
[fv-az585-767:07269] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f31de2969fc]
[fv-az585-767:07269] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f31de242476]
[fv-az585-767:07269] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f31de2287f3]
[fv-az585-767:07269] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f31de6a2b9e]
[fv-az585-767:07269] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f31de6ae20c]
[fv-az585-767:07269] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f31de6ae277]
[fv-az585-767:07269] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f31de6ae52b]
[fv-az585-767:07269] [ 8] plumed(+0x14254)[0x5583684dc254]
[fv-az585-767:07269] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f31de229d90]
[fv-az585-767:07269] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f31de229e40]
[fv-az585-767:07269] [11] plumed(+0x14eb5)[0x5583684dceb5]
[fv-az585-767:07269] *** End of error message ***
</pre>
{% endraw %}
