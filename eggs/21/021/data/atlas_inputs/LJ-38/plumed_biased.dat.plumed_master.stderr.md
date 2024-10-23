**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/LJ-38/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1016-35:07656] *** Process received signal ***
[fv-az1016-35:07656] Signal: Aborted (6)
[fv-az1016-35:07656] Signal code:  (-6)
[fv-az1016-35:07656] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f89bca42520]
[fv-az1016-35:07656] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f89bca969fc]
[fv-az1016-35:07656] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f89bca42476]
[fv-az1016-35:07656] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f89bca287f3]
[fv-az1016-35:07656] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f89bcea2b9e]
[fv-az1016-35:07656] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f89bceae20c]
[fv-az1016-35:07656] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f89bceae277]
[fv-az1016-35:07656] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f89bceae52b]
[fv-az1016-35:07656] [ 8] plumed_master(+0x14254)[0x55ec66e51254]
[fv-az1016-35:07656] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f89bca29d90]
[fv-az1016-35:07656] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f89bca29e40]
[fv-az1016-35:07656] [11] plumed_master(+0x14eb5)[0x55ec66e51eb5]
[fv-az1016-35:07656] *** End of error message ***
</pre>
{% endraw %}
