**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_VAC/plumed_VAC.dat   
(download [zipped raw stdout](plumed_VAC.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: TICA ARG=Prot_norm,wBpock_norm,ab_t,lig_OW_large_norm EIGEN_NUMBERS=4 LAGGED_TIME=150000 TAU_NUMBER=5000 STEP_SIZE=0.5 LOGWEIGHTS=rw
Maybe a missing space or a typo?
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14151] *** Process received signal ***
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14151] Signal: Aborted (6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14151] Signal code:  (-6)
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14151] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x354b0)[0x7fb3b428b4b0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14151] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x38)[0x7fb3b428b428]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14151] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x16a)[0x7fb3b428d02a]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14151] [ 3] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(_ZN9__gnu_cxx27__verbose_terminate_handlerEv+0x16d)[0x7fb3b48c584d]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14151] [ 4] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d6b6)[0x7fb3b48c36b6]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14151] [ 5] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d701)[0x7fb3b48c3701]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14151] [ 6] /usr/lib/x86_64-linux-gnu/libstdc++.so.6(+0x8d919)[0x7fb3b48c3919]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14151] [ 7] plumed[0x40ec85]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14151] [ 8] plumed[0x40f082]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14151] [ 9] plumed[0x409fe0]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14151] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf0)[0x7fb3b4276830]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14151] [11] plumed[0x40a0a9]
[travis-job-8788fb13-4898-4c73-8dd1-99974306413e:14151] *** End of error message ***
</pre>
{% endraw %}
