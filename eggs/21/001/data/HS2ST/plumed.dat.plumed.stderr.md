**Project ID:** [plumID:21.001]({{ '/' | absolute_url }}eggs/21/001/)  
Stderr for source:  HS2ST/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::std_bad_alloc'
  what():  std::bad_alloc
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07898] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07898] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07898] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07898] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fb68b2374b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07898] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fb68b237428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07898] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fb68b23902a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07898] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fb68b87184d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07898] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fb68b86f6b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07898] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fb68b86f701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07898] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fb68b86f919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07898] [ 7] plumed[0x40eeb7]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07898] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07898] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07898] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fb68b222830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07898] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:07898] *** End of error message ***
</pre>
{% endraw %}
