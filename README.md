# AVX trigonometric, exponential and log functions

This all started back in the day as an excercise to learn AVX, building on the [SSE version](http://gruntthepeon.free.fr/ssemath/).

Although this softare still compiles under gcc (version 12.3.0) using the `-O2 -mavx`, I put it here for historical reasons, since the original hosted web site `http://software-lisc.fbk.eu/avx_mathfun/` is not available anymore.
More up-to-date AVX versions can be found [here](https://github.com/reyoung/avx_mathfun), and there is also an AVX2 fork [here](https://github.com/yuyichao/avx2_mathfun).

This code somehow made its way into [pytorch](https://github.com/pytorch/pytorch/blob/main/aten/src/ATen/native/cpu/avx_mathfun.h), which turned out to be a pleasant surprise.
