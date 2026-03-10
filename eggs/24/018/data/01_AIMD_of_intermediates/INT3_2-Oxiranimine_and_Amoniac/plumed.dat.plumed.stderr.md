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
[runnervm0kj6c:07778] *** Process received signal ***
[runnervm0kj6c:07778] Signal: Aborted (6)
[runnervm0kj6c:07778] Signal code:  (-6)
[runnervm0kj6c:07778] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f47eaa45330]
[runnervm0kj6c:07778] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f47eaa9eb2c]
[runnervm0kj6c:07778] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f47eaa4527e]
[runnervm0kj6c:07778] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f47eaa288ff]
[runnervm0kj6c:07778] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f47eaea5ff5]
[runnervm0kj6c:07778] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f47eaebb0da]
[runnervm0kj6c:07778] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f47eaea5a55]
[runnervm0kj6c:07778] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f47eaea5a6f]
[runnervm0kj6c:07778] [ 8] plumed(+0x146dd)[0x563616a7d6dd]
[runnervm0kj6c:07778] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f47eaa2a1ca]
[runnervm0kj6c:07778] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f47eaa2a28b]
[runnervm0kj6c:07778] [11] plumed(+0x15365)[0x563616a7e365]
[runnervm0kj6c:07778] *** End of error message ***
</pre>
{% endraw %}
