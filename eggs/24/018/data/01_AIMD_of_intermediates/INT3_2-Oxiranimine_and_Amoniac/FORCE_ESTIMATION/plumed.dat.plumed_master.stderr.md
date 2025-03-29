**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT3_2-Oxiranimine_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1701-508:62134] *** Process received signal ***
[fv-az1701-508:62134] Signal: Aborted (6)
[fv-az1701-508:62134] Signal code:  (-6)
[fv-az1701-508:62134] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f30aac45330]
[fv-az1701-508:62134] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f30aac9eb2c]
[fv-az1701-508:62134] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f30aac4527e]
[fv-az1701-508:62134] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f30aac288ff]
[fv-az1701-508:62134] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f30ab0a5ff5]
[fv-az1701-508:62134] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f30ab0bb0da]
[fv-az1701-508:62134] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f30ab0a5a55]
[fv-az1701-508:62134] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f30ab0a5a6f]
[fv-az1701-508:62134] [ 8] plumed_master(+0x146dd)[0x563b2b04b6dd]
[fv-az1701-508:62134] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f30aac2a1ca]
[fv-az1701-508:62134] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f30aac2a28b]
[fv-az1701-508:62134] [11] plumed_master(+0x15365)[0x563b2b04c365]
[fv-az1701-508:62134] *** End of error message ***
</pre>
{% endraw %}
