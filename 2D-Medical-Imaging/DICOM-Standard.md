
## Scenario

 Jerry is outside working in his yard and drops a heavy object on his left foot. He's pretty sure that's broken, so he has his wife rush him to the emergency room at Hospital A. The emergency room doctor orders a set of x-rays of both his left and right feet, ankles, and tibia. Turns out, there were also some rusty nails sticking out of that heavy object that gave Jerry some nasty cuts, so the ER doc also orders some blood work, gives Jerry a tetanus shot, and a few stitches. The ER doc asks Jerry if he's been having any other symptoms, and Jerry tells him that he's been feeling pretty light-headed all day, since he woke up in the morning, and that he has a history of fainting because of his low blood pressure. After a full physical examination, the ER doctor determines that there's nothing wrong with him other than his broken foot, but that he's just dehydrated and needs to take it easy. Unfortunately, he also needs to see an orthopedic surgeon to reset his foot, and Hospital A doesn't have one on duty on the weekends, so they send him to Hospital B where there is an orthopedic doctor. While Jerry is in the car on his way to Hospital B, Hospital B receives his full DICOM study and Hospital A's radiology report, but nothing else.

 ## Questions
 ### What does Hospital B know about Jerry before he arrives?
- Do they know that he has a broken foot? Why or why not?
- Do they know what the results were of Jerry's blood work? Why or why not?
- Do they know that he has a history of low blood pressure? Why or why not?

### `Answers`
- Yes, Hospital B will know jerry have broken foot. A radiologist and orthopedic surgeon can look at DICOM file to see the fracture foot. 
- Hospital B will not know results of Jerry's blood work because it is  not included in DICOM. It comes under clinical data and stored in EMR .
- Hospital B will not know about Jerry's medical history for similar reasons it is not stored in DICOM study.