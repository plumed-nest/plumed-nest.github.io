**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_Cyanomethanolate_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1693-957:62141] *** Process received signal ***
[fv-az1693-957:62141] Signal: Aborted (6)
[fv-az1693-957:62141] Signal code:  (-6)
[fv-az1693-957:62141] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc98c645330]
[fv-az1693-957:62141] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc98c69eb2c]
[fv-az1693-957:62141] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc98c64527e]
[fv-az1693-957:62141] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc98c6288ff]
[fv-az1693-957:62141] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc98caa5ff5]
[fv-az1693-957:62141] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc98cabb0da]
[fv-az1693-957:62141] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc98caa5a55]
[fv-az1693-957:62141] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc98caa5a6f]
[fv-az1693-957:62141] [ 8] plumed_master(+0x146dd)[0x55b001a0b6dd]
[fv-az1693-957:62141] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc98c62a1ca]
[fv-az1693-957:62141] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc98c62a28b]
[fv-az1693-957:62141] [11] plumed_master(+0x15365)[0x55b001a0c365]
[fv-az1693-957:62141] *** End of error message ***
</pre>
{% endraw %}
