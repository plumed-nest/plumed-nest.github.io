**Project ID:** [plumID:20.012]({{ '/' | absolute_url }}eggs/20/012/)  
Stderr for source:  fun_SWISH/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at IFile.cpp:113, function virtual PLMD::IFile& PLMD::IFile::open(const string&)
+++ assertion failed: do_exist
+++ message follows +++
file cmap.dat cannot be found
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09647] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09647] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09647] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09647] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7f75e3cf84b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09647] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7f75e3cf8428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09647] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7f75e3cfa02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09647] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7f75e433284d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09647] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7f75e43306b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09647] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7f75e4330701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09647] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7f75e4330969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09647] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09647] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7f75e3ce3830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09647] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:09647] *** End of error message ***
</pre>
{% endraw %}
