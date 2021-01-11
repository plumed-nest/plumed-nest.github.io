**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_VAC/plumed_VAC.dat   
(download [zipped raw stdout](plumed_VAC.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:704, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: TICA ARG=Prot_norm,wBpock_norm,ab_t,lig_OW_large_norm EIGEN_NUMBERS=4 LAGGED_TIME=150000 TAU_NUMBER=5000 STEP_SIZE=0.5 LOGWEIGHTS=rw
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14154] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14154] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14154] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14154] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fd71b1004b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14154] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fd71b100428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14154] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fd71b10202a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14154] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fd71b73a84d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14154] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fd71b7386b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14154] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fd71b738701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14154] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x49)[0x7fd71b738969]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14154] [ 7] plumed_master[0x40a072]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14154] [ 8] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fd71b0eb830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14154] [ 9] plumed_master[0x40a0e9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14154] *** End of error message ***
</pre>
{% endraw %}
