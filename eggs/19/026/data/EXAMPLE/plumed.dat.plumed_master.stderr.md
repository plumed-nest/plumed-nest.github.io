**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[fv-az975-395:07980] *** Process received signal ***
[fv-az975-395:07980] Signal: Aborted (6)
[fv-az975-395:07980] Signal code:  (-6)
[fv-az975-395:07980] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f19e1442520]
[fv-az975-395:07980] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f19e14969fc]
[fv-az975-395:07980] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f19e1442476]
[fv-az975-395:07980] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f19e14287f3]
[fv-az975-395:07980] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f19e18a2b9e]
[fv-az975-395:07980] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f19e18ae20c]
[fv-az975-395:07980] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f19e18ae277]
[fv-az975-395:07980] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f19e18ae52b]
[fv-az975-395:07980] [ 8] plumed_master(+0x14254)[0x55d9fe964254]
[fv-az975-395:07980] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f19e1429d90]
[fv-az975-395:07980] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f19e1429e40]
[fv-az975-395:07980] [11] plumed_master(+0x14eb5)[0x55d9fe964eb5]
[fv-az975-395:07980] *** End of error message ***
</pre>
{% endraw %}
