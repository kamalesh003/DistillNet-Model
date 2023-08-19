# DistillNet-Model


1.) Creating a teacher model
2.) Performing knowledge distillation
3.) Training a student model
4.) Saving the student model
5.) Test the student model

The steps you've taken are as follows:

 -->generated sample data and defined the architecture of the teacher model, compiling it with the appropriate loss function.
 -->trained the teacher model using the same data for both inputs and targets.
 -->performed knowledge distillation by using the teacher model's predictions as soft targets for the student model, and you scaled the targets using a temperature parameter.
 -->defined the architecture of the student model, compiled it, and trained it using the distilled targets.
 -->saved the trained student model to a file using save_model.
 -->loaded the saved student model using load_model.
 -->generated new test data and used the loaded student model to make predictions on the new data.
