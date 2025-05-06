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
[fv-az1050-229:62365] *** Process received signal ***
[fv-az1050-229:62365] Signal: Aborted (6)
[fv-az1050-229:62365] Signal code:  (-6)
[fv-az1050-229:62365] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f33eee45330]
[fv-az1050-229:62365] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f33eee9eb2c]
[fv-az1050-229:62365] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f33eee4527e]
[fv-az1050-229:62365] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f33eee288ff]
[fv-az1050-229:62365] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f33ef2a5ff5]
[fv-az1050-229:62365] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f33ef2bb0da]
[fv-az1050-229:62365] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f33ef2a5a55]
[fv-az1050-229:62365] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f33ef2a5a6f]
[fv-az1050-229:62365] [ 8] plumed(+0x146dd)[0x5600c3a746dd]
[fv-az1050-229:62365] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f33eee2a1ca]
[fv-az1050-229:62365] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f33eee2a28b]
[fv-az1050-229:62365] [11] plumed(+0x15365)[0x5600c3a75365]
[fv-az1050-229:62365] *** End of error message ***
</pre>
{% endraw %}
