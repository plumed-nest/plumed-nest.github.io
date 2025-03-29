**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_FM/plumed_FM.dat   
Download: [zipped raw stdout](plumed_FM.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_FM.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "FPS" is not known.
[fv-az1344-582:68583] *** Process received signal ***
[fv-az1344-582:68583] Signal: Aborted (6)
[fv-az1344-582:68583] Signal code:  (-6)
[fv-az1344-582:68583] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6e84a45330]
[fv-az1344-582:68583] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6e84a9eb2c]
[fv-az1344-582:68583] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6e84a4527e]
[fv-az1344-582:68583] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6e84a288ff]
[fv-az1344-582:68583] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6e84ea5ff5]
[fv-az1344-582:68583] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6e84ebb0da]
[fv-az1344-582:68583] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6e84ea5a55]
[fv-az1344-582:68583] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6e84ea5a6f]
[fv-az1344-582:68583] [ 8] plumed_master(+0x146dd)[0x55671e8506dd]
[fv-az1344-582:68583] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6e84a2a1ca]
[fv-az1344-582:68583] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6e84a2a28b]
[fv-az1344-582:68583] [11] plumed_master(+0x15365)[0x55671e851365]
[fv-az1344-582:68583] *** End of error message ***
</pre>
{% endraw %}
