**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[fv-az1344-582:60826] *** Process received signal ***
[fv-az1344-582:60826] Signal: Aborted (6)
[fv-az1344-582:60826] Signal code:  (-6)
[fv-az1344-582:60826] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f492a845330]
[fv-az1344-582:60826] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f492a89eb2c]
[fv-az1344-582:60826] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f492a84527e]
[fv-az1344-582:60826] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f492a8288ff]
[fv-az1344-582:60826] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f492aca5ff5]
[fv-az1344-582:60826] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f492acbb0da]
[fv-az1344-582:60826] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f492aca5a55]
[fv-az1344-582:60826] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f492aca5a6f]
[fv-az1344-582:60826] [ 8] plumed(+0x146dd)[0x55e098d5d6dd]
[fv-az1344-582:60826] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f492a82a1ca]
[fv-az1344-582:60826] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f492a82a28b]
[fv-az1344-582:60826] [11] plumed(+0x15365)[0x55e098d5e365]
[fv-az1344-582:60826] *** End of error message ***
</pre>
{% endraw %}
