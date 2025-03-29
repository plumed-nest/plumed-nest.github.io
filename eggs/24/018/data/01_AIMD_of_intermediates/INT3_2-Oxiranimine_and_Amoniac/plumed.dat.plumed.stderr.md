**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT3_2-Oxiranimine_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1701-508:62169] *** Process received signal ***
[fv-az1701-508:62169] Signal: Aborted (6)
[fv-az1701-508:62169] Signal code:  (-6)
[fv-az1701-508:62169] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f71a0845330]
[fv-az1701-508:62169] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f71a089eb2c]
[fv-az1701-508:62169] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f71a084527e]
[fv-az1701-508:62169] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f71a08288ff]
[fv-az1701-508:62169] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f71a0ca5ff5]
[fv-az1701-508:62169] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f71a0cbb0da]
[fv-az1701-508:62169] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f71a0ca5a55]
[fv-az1701-508:62169] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f71a0ca5a6f]
[fv-az1701-508:62169] [ 8] plumed(+0x146dd)[0x55637ff126dd]
[fv-az1701-508:62169] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f71a082a1ca]
[fv-az1701-508:62169] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f71a082a28b]
[fv-az1701-508:62169] [11] plumed(+0x15365)[0x55637ff13365]
[fv-az1701-508:62169] *** End of error message ***
</pre>
{% endraw %}
