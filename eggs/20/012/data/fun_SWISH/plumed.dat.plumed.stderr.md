**Project ID:** [plumID:20.012]({{ '/' | absolute_url }}eggs/20/012/)  
Stderr for source:  fun_SWISH/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at IFile.cpp:113, function virtual PLMD::IFile& PLMD::IFile::open(const string&)
+++ assertion failed: do_exist
+++ message follows +++
file cmap.dat cannot be found
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09635] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09635] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09635] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09635] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f876986b4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09635] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f876986b428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09635] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f876986d02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09635] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f8769ea584d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09635] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f8769ea36b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09635] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f8769ea3701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09635] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7f8769ea3919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09635] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09635] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09635] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09635] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f8769856830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09635] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09635] *** End of error message ***
</pre>
{% endraw %}
