**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT3_2-Oxiranimine_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1050-229:62314] *** Process received signal ***
[fv-az1050-229:62314] Signal: Aborted (6)
[fv-az1050-229:62314] Signal code:  (-6)
[fv-az1050-229:62314] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2941e45330]
[fv-az1050-229:62314] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2941e9eb2c]
[fv-az1050-229:62314] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2941e4527e]
[fv-az1050-229:62314] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2941e288ff]
[fv-az1050-229:62314] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f29422a5ff5]
[fv-az1050-229:62314] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f29422bb0da]
[fv-az1050-229:62314] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f29422a5a55]
[fv-az1050-229:62314] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f29422a5a6f]
[fv-az1050-229:62314] [ 8] plumed(+0x146dd)[0x55a585e176dd]
[fv-az1050-229:62314] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2941e2a1ca]
[fv-az1050-229:62314] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2941e2a28b]
[fv-az1050-229:62314] [11] plumed(+0x15365)[0x55a585e18365]
[fv-az1050-229:62314] *** End of error message ***
</pre>
{% endraw %}
