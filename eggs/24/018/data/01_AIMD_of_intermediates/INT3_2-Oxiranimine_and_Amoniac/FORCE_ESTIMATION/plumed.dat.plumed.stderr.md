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
[fv-az1701-508:62117] *** Process received signal ***
[fv-az1701-508:62117] Signal: Aborted (6)
[fv-az1701-508:62117] Signal code:  (-6)
[fv-az1701-508:62117] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f313a845330]
[fv-az1701-508:62117] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f313a89eb2c]
[fv-az1701-508:62117] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f313a84527e]
[fv-az1701-508:62117] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f313a8288ff]
[fv-az1701-508:62117] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f313aca5ff5]
[fv-az1701-508:62117] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f313acbb0da]
[fv-az1701-508:62117] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f313aca5a55]
[fv-az1701-508:62117] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f313aca5a6f]
[fv-az1701-508:62117] [ 8] plumed(+0x146dd)[0x5610118126dd]
[fv-az1701-508:62117] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f313a82a1ca]
[fv-az1701-508:62117] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f313a82a28b]
[fv-az1701-508:62117] [11] plumed(+0x15365)[0x561011813365]
[fv-az1701-508:62117] *** End of error message ***
</pre>
{% endraw %}
