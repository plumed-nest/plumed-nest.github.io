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
[fv-az1693-854:11801] *** Process received signal ***
[fv-az1693-854:11801] Signal: Aborted (6)
[fv-az1693-854:11801] Signal code:  (-6)
[fv-az1693-854:11801] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f449f845330]
[fv-az1693-854:11801] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f449f89eb2c]
[fv-az1693-854:11801] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f449f84527e]
[fv-az1693-854:11801] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f449f8288ff]
[fv-az1693-854:11801] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f449fca5ff5]
[fv-az1693-854:11801] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f449fcbb0da]
[fv-az1693-854:11801] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f449fca5a55]
[fv-az1693-854:11801] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f449fca5a6f]
[fv-az1693-854:11801] [ 8] plumed_master(+0x146dd)[0x55579e3ae6dd]
[fv-az1693-854:11801] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f449f82a1ca]
[fv-az1693-854:11801] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f449f82a28b]
[fv-az1693-854:11801] [11] plumed_master(+0x15365)[0x55579e3af365]
[fv-az1693-854:11801] *** End of error message ***
</pre>
{% endraw %}
