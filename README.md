# Markdown-Testing
{VegetableID, MaterialID} -> {Name, Seeding, GerminationTemperature, GerminationDays, HarvestingTime, GrowTemperature, HavestingInstruction, Images.ImageID, Description, OptionalMaterial}

{VegetableID } -> {Name, Seeding, GerminationTemperature, GerminationDays, HarvestingTime, GrowTemperature, HavestingInstruction, ImageID }

{MaterialID} -> {MaterialName, Description, OptionalMaterial}

{SicknessID } -> { Sickness, Symptoms, Solutions }

{SicknessID, VegetableID } -> { Sickness, Symptoms, Solutions, Name, Seeding, GerminationTemperature, GerminationDays, HarvestingTime, GrowTemperature, HavestingInstruction, ImageID }

{ ImageID  } -> { ImageURL, Description }

{ProjectID } -> {ProjectName, ChecklistReminder, ChapterReminder, BookmarkChapter}

{ ProjectID, VegetableID, PlantedDate } -> { Name, Seeding, GerminationTemperature, GerminationDays, HarvestingTime, GrowTemperature, HavestingInstruction, ImageID, ProjectName, ChecklistReminder, ChapterReminder, LeftOffChapter}

{StepID} -> {ChapterID, StepNumber, Content}

{TipID} -> {Name, Description, ChapterID}

{ChapterID} -> {ChapterNumber, WaitTime, ChapterName}
