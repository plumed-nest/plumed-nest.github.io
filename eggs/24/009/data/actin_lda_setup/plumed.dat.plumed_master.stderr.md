**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[runnervm0kj6c:07852] *** Process received signal ***
[runnervm0kj6c:07852] Signal: Aborted (6)
[runnervm0kj6c:07852] Signal code:  (-6)
[runnervm0kj6c:07852] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc034c45330]
[runnervm0kj6c:07852] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc034c9eb2c]
[runnervm0kj6c:07852] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc034c4527e]
[runnervm0kj6c:07852] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc034c288ff]
[runnervm0kj6c:07852] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc0350a5ff5]
[runnervm0kj6c:07852] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc0350bb0da]
[runnervm0kj6c:07852] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc0350a5a55]
[runnervm0kj6c:07852] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc0350a5a6f]
[runnervm0kj6c:07852] [ 8] plumed_master(+0x146dd)[0x5580a96916dd]
[runnervm0kj6c:07852] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc034c2a1ca]
[runnervm0kj6c:07852] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc034c2a28b]
[runnervm0kj6c:07852] [11] plumed_master(+0x15365)[0x5580a9692365]
[runnervm0kj6c:07852] *** End of error message ***
</pre>
{% endraw %}
