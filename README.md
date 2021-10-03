### Thanks for extending the deadline multiple times, this has helped me to incrementally focus rather than giving up or ignoring easily.
### I think I have invested enough time to explore things and learnt quite a lot, atleast reading the code, concepts are WIP.

#### Alright, about the Final Submission.
Here is the current status, I will send an email once I finish things up and hopefully will not be too late to not qualify for Phase2.

### Part 2:
* I have been able to understand the GT requirements and know how to create it.
  - I have discovered multiple ways and spent quite some time to get atleast one of them to work.
  - This needs a deep understanding of how annotations are used in coco, were created and linked between object detection and stuff segmentation and now to panoptic. I shyed away from even exploring Keypoint/Captions. *(System Overload)*. I am sure they will take more time to understand.
  - To summarize, Because of OOM *(Out of Memory and Out of Moolah)* or lack of time, we *(I am hoping its not just me, I know some have really good systems at their disposal)* have to figure out ways to either combine annotations *(to get more work done with lesser images)*, or to finetune the model postprocessing to get things done. With no OOM, I would happily run two batches of our segmented things and stuff images separately and see how the model would fare. To build GT, the above two options were explored.
  - Finishing up gathering the training logs etc., thanks to colab, will submit this report soon. I haven't been able to deal with the entire dataset and all classes. So, trying my best to add as much as I can.
  - The challenge is to get GT and segmentation in the form of segment info for training usage in  Part 3.

### Part 3:
* This was a real problem when the assignment was published, and like you mentioned, most of them stop at segmentation. But, over the last month, actually I have worked only over the last month, I know its almost 2 months that was given for this capstone, there have been a lot of updates.
  - First started with the link that was given in S14, about tweaking the code, was a handsome full to understand DETR for OD.
  - Reading multiple times, and finally getting the notebook to work *( with incorrect pytorch versions, updates and what not)*, I progressed to understand that BB detection is important and PO *(in DETR's case, cannot be performed without a good OD/BB detection)*. Also, PO quality becomes an add-on over the quality of OD. And since the problem statement stated that we need to add stuff and not other things from coco class, it isn't straight forward anymore. *(finding for an hack, exploring datasets, all of this makes sure that the concept are understood fully to get things to work)*. 
  - Now with the classic issue of finetuning, the issue was to read issues and understand:
* Challenges/Questions are/were:
  - How to finetune?
  - num_classes - how does it work, how to change it and why is it such a high number.
  - Input, Output Format, Predictions, Getting loss curves, Optimizers to use etc etc.
  
* I have finished a trial run for POSegm and once the dataset for Part 2 is available, I will publish a report.
    
 ### I am expecting to finish by this week - 10/10 *(have two capstones to finish)*. Hopefully I will be able to squeeze in the minimum marks along with EVA5 to qualify.
 
 ### Thank You
