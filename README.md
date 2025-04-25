# Automatic-Number-plate-authentication
This project helps in authentication of indian vehicle number plates With the increasing number of cars and bikes on the road, correct vehicle identification is a crucial activity for transport authorities. Among the fundamental aspects of this is maintaining standard vehicle number plates, following pre-defined formats. Any deviation from these formats, either accidentally or intentionally, triggers issues in law enforcement, vehicle location, and toll collection. Therefore, an automatic vehicle number plate validation system is necessary to stimulate standard compliance and impose legal action for non-compliance.

To solve this proble I developed a project which employees DeepLearning and Computer Vision techniques as follows--------------------------------> ---->The system takes vehicle number plate images as input, categorizing them into two distinct classes: "In Format" and "Not in Format." The approach leverages a ResNet-50 architecture trained on RGB image data ---->For number plates identified as "Not in Format, where a YOLOv10 model is employed to extract the vehicle’s number ---->From this using Paddle OCR I extracted the vehicle number plate Characters ---->This automated solution aims to streamline the identification and penalization of vehicles that do not adhere to number plate standards, ultimately contributing to a more organized and efficient vehicle identification process.

Further Advancements-
----> The extracted vehicle number can be directely stored in database to maintain the entry time and exit time in parking lots or in any other places to improve the security protocols

Automatic-Number-Plate-Authentication-/README.md at
