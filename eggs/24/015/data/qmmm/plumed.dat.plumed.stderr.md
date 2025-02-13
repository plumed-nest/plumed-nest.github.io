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
[fv-az1046-619:05744] *** Process received signal ***
[fv-az1046-619:05744] Signal: Aborted (6)
[fv-az1046-619:05744] Signal code:  (-6)
[fv-az1046-619:05744] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe518045330]
[fv-az1046-619:05744] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe51809eb2c]
[fv-az1046-619:05744] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe51804527e]
[fv-az1046-619:05744] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe5180288ff]
[fv-az1046-619:05744] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe5184a5ff5]
[fv-az1046-619:05744] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe5184bb0da]
[fv-az1046-619:05744] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe5184a5a55]
[fv-az1046-619:05744] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe5184a5a6f]
[fv-az1046-619:05744] [ 8] plumed(+0x146dd)[0x561bceaad6dd]
[fv-az1046-619:05744] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe51802a1ca]
[fv-az1046-619:05744] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe51802a28b]
[fv-az1046-619:05744] [11] plumed(+0x15365)[0x561bceaae365]
[fv-az1046-619:05744] *** End of error message ***
</pre>
{% endraw %}
