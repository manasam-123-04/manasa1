# manasa1
{
 "cells": [
  {
   "cell_type": "code",
   "execution_count": 1,
   "id": "7b44445a",
   "metadata": {},
   "outputs": [],
   "source": [
    "def generate_time_series(batch_size,n_steps):\n",
    "    freq1,freq2,offset1,offset2=np.random.rand(4,batch_size,1)\n",
    "    time=np.linspace(0,1,n_steps)\n",
    "    series=0.5*np.sin((time-offsets1)*(freq1*10+10))\n",
    "    series+=0.2*np.sin((time-offsets2)*(freq*20+20))\n",
    "    series+=0.1*(np.random.rand(batch_size,n_steps)-0.5)\n",
    "    return series[...,np.newaxis].astype(np.float32)"
   ]
  },
