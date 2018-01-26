# Markdown-Testing
Vegetable (VegetableID, ImageID, Name, Seeding, GerminationTemperature, GerminationDays, HarvestingTime, GrowTemperature, HarvestInstruction)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Vegetable (ImageID) must exist in Image (ImageID)

Material Per Vegetable (MaterialID, VegetableID)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Material Per Vegetable (MaterialID) must exist in Material (MaterialID)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Material Per Vegetable (VegetableID) must exist in Vegetable (VegetableID)

Saved Project (ProjectID, BookmarkChapter, ProjectName, ChecklistReminder, ChapterReminder)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Saved Project (BookmarkChapter) must exist in Chapter (ChapterID)

Sickness Per Vegetable (SicknessID, VegetableID)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Sickness Per Vegetable (SicknessID) must exist in Sickness (SicknessID)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Sickness Per Vegetable (VegetableID) must exist in Vegetable (VegetableID)

Planted Vegetable (ProjectID, VegetableID, PlantedDate)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Planted Vegetable (ProjectID) must exist in Saved Project (ProjectID)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Planted Vegetable (VegetableID) must exist in Vegetable (VegetableID)

Material (MaterialID, MaterialName, Description, OptionalMaterial)

Step (StepID, ChapterID, StepNumber, Content)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Step (ChapterID) must exist in Chapter (ChapterID)

Chapter (ChapterID, ChapterNumber, WaitTime, ChapterName)

Sickness(SicknessID, Sickness, Symptoms, Solutions)

Tip( TipID, ChapterID, Name, Description)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tip(ChapterID) must exists in Chapter (ChapterID)

Image( ImageID, ImageURL, Description )
