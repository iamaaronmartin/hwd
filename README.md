## To add:  
- Create a template deck for designers to populate for each time they present so there is a standard model
- Give an example of how you might name layers effectively (top to bottom)
- In file structure: ability to break out the sub feature into a different sketch file to avoid bloating files
- Github pages structure

## Think about adding:  
- Change color names to Fuji proper names?
- Examples for folder/file/artboard structure
- Structure of Sketch Libraries



- - - 



# How we design
As a large team, working on large and complex products, we have developed a system that helps us all stay organized. With a defined starting point, we're all able to work together on overlapping platforms, products, and features without having large conversations and transfers of domain knowledge. Retaining insight into what each other is doing helps us all share ideas and create better products.

- - -

# What we value
Designing products is the act of making choices and decisions. We know whether or not those decisions fit within a fundamental orientation of our team's point of view by having a defined philosophy on what we believe our design to be.

When designing products, these design values help guide us into appropriate choices.

1. We design cohesive experiences, until we don't.
2. We use validated building blocks. New for the sole sake of being new doesn't help our users.
3. Design is iterative, because no feature or product is ever truly final.
4. We work to understand the problem we are solving and the value that a solution brings to our users.
5. Profits for advertisers should not disrupt our user's needs.
6. We make products that we ourselves value.


# What is good design?
As we design and iterate on features and products, it's important to define what a successful outcome is. As we start each feature, we should ask and answer the following questions:

1. Is it meeting a demand for a specific problem?
2. Is it reinventing low-leverage things that don't need to be reinvented?
3. Is it consistent with itself?
4. Is it consistent with things around it?
5. Is it consistent with Yahoo as a whole?
6. Is it moving the product forward?
7. Are there clearly defined metrics that we are designing against?

After we launch, and have gathered feedback, a list of additional questions can be answered to validate our solution:

1. Did we meet, exceed, or fall short of the target metrics?
2. As a piece of a larger puzzle, does this fit in with, and enhance the existing product and solutions inside it?
3. What would/could/should we change?

If we can successfully answer these questions, we're going to be pushing out great products and solutions. And if we fall short of that goal, we will have set ourselves up to figure out quickly what we've learned and where we should move towards.



- - -



# How we communicate
Knowing what each other is working on will allow us to deliver high-quality work, share insights, and remove overlapping tasks. The constant and scheduled communication with help us to build and share institutional knowledge of what Mail, who we are building it for, and what needs they want met.

## Weekly stand-up
We have simple, weekly design stand-ups formatted in the following fashion:
- Each person shares what they worked on last week, for a maximum of 5 minutes
- If, as a group, we touch upon something that needs more in-depth exploration, we will schedule a dedicated meeting for us to discuss it as a team
- The next person begins
- The end

## In-depth feature review
When showcasing a feature, it's important to meet and gather feedback in a way that is productive and beneficial.

**As a presenter:**
- Before showing any designs, tell everyone what you're presenting
- Give a concise summary of the problem you're solving and the solution you're aiming to deliver
- Clearly state the level of feedback you're looking to gather
- Ask someone to be a dedicated note-taker for the meeting
- Present the solution

Defining your feature in the terms of a Job Story, can help you clearly articulate your problem and proposed solution.

Tips for writing a Job Story:
[Designing features using Job Stories](https://blog.intercom.com/using-job-stories-design-features-ui-ux/)
[5 Tips For Writing A Job Story](https://jtbd.info/5-tips-for-writing-a-job-story-7c9092911fc9)
[Your Job Story Needs A Struggling Moment](https://jtbd.info/your-job-story-needs-a-struggling-moment-c03de87c6026)

This will help you alleviate the ambiguities and assumptions commonly found in a User Story. Personas are fundamentally made up, not real, and full of prejudices.

If needed, provide a clear visual example of how the feature lives inside of the larger system.

**As a participant:**
- Aim to ask question as they will help verify choices and allow the presenter to open up inside the assumptions they have made
- Make sure your underlying assumptions are addressed
- Refrain from offering opinions, and make sure that we're addressing specific pieces and creating actionable points
- Leave the meeting on-time



- - -



# How we build

## Folder structure

Products are organized in each Team Drive in a way that allows for everyone else to find each others' work, should that be needed (which it will be).

Folders are set in "Sentence case" and follow a similar hierarchical structure to help keep us all organized and consistent:  
Platform / Feature / Sub platform

**Example:**  
Mobile / Message list / iOS

Each feature has a similar set of starting folders as well:  
"_ archive"  
"_ documents"    
"_ mocks"

### _ archive folder
This is exactly what you think it is. If you want to save it but don't need access to it, place it here.

### _ documents folder
Place Google Docs here. This does two things: it makes connected documents easily accessible, and it shares them to the entire team without having to invite them directly to every document needed for that feature.

### _ mocks folder
Flat PNGs live here, placed into a folder for each sub-feature. Dated folders (yyyy-mmdd) will keep things organized and keep a historical record.

**Example:**  
_ mocks / Contacts / Contact card / iOS / 2017-0810



- - -



## File structure
All file names are Sentence case, and in any instance where spaces aren't allow, a dash(-) should be used in lieu of a space.

A Sketch file should exist for each feature, on each platform. Each feature file should contain past, present, and future versions of the feature. Wireframes for a feature are included in the same file as the working design.

### Pages
Sketch Pages control and organize versioning, with the Sketch Page of the current production design named (v#) + (.current). All archived artboards and elements should reside on an "Archive" Sketch Page. If multiple sub-features are included in a file, the sub-feature name should be prefixed to the Page name.

**Example page set:**  
![Page naming example](https://git.corp.yahoo.com/pages/aam/comms-design/images/hwd/hwd-page-naming.png)

**Example sub-feature set:**  
![Page naming example with sub-features](https://git.corp.yahoo.com/pages/aam/comms-design/images/hwd/hwd-page-naming-2.png)

### Artboards
Inside of our Sketch Page, our Artboards should read and function in top-to-bottom order and be properly named using the [Artboard Tricks plugin](https://github.com/romannurik/Sketch-ArtboardTricks). Using the Artboard Tricks plugin will do two things: we arrange our Artboards in a grid and prefix Artboard names with a number series. This will help keep file exports in order, and allow for easily identifiable entities to share.

Horizontally aligned Artboards should be considered a unique flow or grouping. Each new Artboard row should relate to the Feature the file is designing, but should be a logically new grouping.

**Example:**  
![Artboard naming example](https://git.corp.yahoo.com/pages/aam/comms-design/images/hwd/hwd-artboard-naming.png)

### Layers and Layer groups
We name our Layers and our Layer Groups, period. Common sense, above everything else, should be applied when doing so. If it's a default name that Sketch has given a Layer or Layer Group, it's incorrect. Layers and Layer Groups in the Layer List, should be arranged to reflect the logical grouping and build of the page elements we're building. As the page design works it's way from the top of the view downward, the Layer List elements should mirror that order.

### Symbols
If an element is repeated throughout a page, feature, or product, it should be a symbol.

We share and collaborate pieces of our app through the native Sketch Library feature. For now, we store the platform Libraries in Dropbox.

**Locations:**  
*Android:* Mail / Sketch Libraries / Mail for Android.sketch  
*iOS:* Mail / Sketch Libraries / Mail for iOS.sketch  
*Norrin:* Mail / Sketch Libraries / Norring.sketch

Changes to individual Library symbols and components should be done with a fair amount of caution and a tremendous amount of communication.

TO keep your files clean and free from possible redundancies I recommend liberally using the [Symbol Organizer](https://www.sketchpacks.com/sonburn/symbol-organizer) plugin in combination with the [Merge duplicate symbols](https://github.com/oodesign/merge-duplicate-symbols) plugin.

For Symbol Organizer, I've found the following to be the most effective:
![Page naming example](https://git.corp.yahoo.com/pages/aam/comms-design/images/hwd/hwd-symbol-organizer.png)

### Color
We use Fuji colors universally and consistently. If it's not Fuji, don't use it. If it's close to Fuji but not an exact Fuji color, change it to the closest Fuji color available. We can import Fuji colors directly in to the Global palette in Sketch so there is no real reason to not have the exact color needed. The [Sketch Palettes](https://github.com/andrewfiorillo/sketch-palettes) plugin will import the [Fuji Palette](https://drive.google.com/open?id=0B3XQlwtpWyzFd1dhVDN3VnhIbmc) file. When importing, choose to save these colors to your Global palette and you'll only ever have to do this process once.

### Accessibility
We aim for apps that everyone can use comfortably. WCAG AA standards are what we are holding ourselves to, and tools like [Color Contrast Analyser for Sketch](https://github.com/getflourish/Sketch-Color-Contrast-Analyser) and [Colour Contrast Analyser for macOS](https://github.com/ThePacielloGroup/CCA-OSX) help us meet those standards.

### Writing
Buttons, headlines, and sub-headlines are set in Sentence case.



- - -



# Design elements
There are two levels of design resources: universally used assets for all Comms products, and Product specific resources used in specific products.

**Example:**  
Commercial sender avatars: Universal asset  
20px icon set: Specific to Norrin

## Asset types
Avatars (people)  
Avatars (commercial entities)  
Fuji icon Symbols (24pt)  
Fuji color Symbols  
Norrin icons Symbols (20pt)  

## Libraries
Each platform has its own singular Sketch Library file. A library file is split in to 4 levels:

### Level 1: Foundational elements
Level 1 symbols don’t include any other symbol(s), and are foundational elements that are more stylistic than they are elemental.

**Examples:**  
- Colors  
- Icons  
- Orb shapes for avatars   
- Background gradients

*Icons:*
An icon Symbol is an exception on the inclusion of another Symbol inside of the Level 1 rules, as it will be composed of an icon glyph, set as a Mask, with a Fuji color swatch Symbol to control the color through it's placement on any Artboard.

### Level 2: Lower-level blocks
Level 2 Symbols contain one or more Level 1 symbols, and are typically stand-alone UI elements.

**Examples:**  
- Form field elements, such as buttons, inputs, radio buttons  
- Cell elements, such as Message list rows  
- Navigational elements like the Ybar  
- Cards

### Level 3: Mid-level blocks
Level 3 Symbols are starting to become complex elements and combine multiple Level 1 and 2 blocks into complex UI views. These are advanced Symbols, which make up large sections of a product page.

**Examples:**  
- Sidebars  
- Right rail  
- Main content areas, such as a Message list or Conversation  

### Level 4: Compositions
These are complex and complete Symbols that compose essentially a complete view of a product screen.

# How we communicate with external teams
Communications is one of the keys to a consistent product. We communicate our designs and decisions through words and visual images, and at several steps throughout the life-cycle of the design.

## Wireframes and UX flows
When designing and working through what a feature or product will be, we share our thoughts through Google Slides, using the [Sync to Slides](https://github.com/websiddu/sync-to-slides) plug-in. This Google Slide file should be saved inside of the corresponding folder location as the source design file, and named in the same fashion as the source file, with the addition of the platform name.

**Example:**  
The Google Slide file for the iOS Contacts list Sketch file should live in the *Mail++ / Contacts / iOS* folder and be named *Contacts list (iOS)*.

## Early iterations of visual design
Early design iterations are treated the same as wireframes and UX flows, and can be shared and commented on in the same fashion, in a Google Slide document.

## How we spec our finalized design files
[Sketch Measure](https://github.com/utom/sketch-measure) is our go-to method for delivering finalized specs to our PM and engineering teams. Spec docs live, by product + platform, in a Git pages site, that is accessible to everyone at Yahoo.

## Asset delivery
The easiest way of keeping assets in order for our engineering teams and ourselves, is to have a single, unified source of truth for delivered assets. Ideally a single Google Drive folder divided by Product and then Platform, so that everyone has access to existing assets.

**Example:**  
[Mail++ asset folder (yo/mailpp)](https://drive.google.com/drive/folders/0BywgQ6vyXklqfnRBMzhFaXhlZlczYnJKVHRNWTN5ei1wNG9mQV9aSlZhMWh5bFI1MTdTRzA)

To help partner with an engineering goal of keeping app bundles light, we compress all of our bitmap images using two tools: [ImageAlpha](https://pngmini.com/) and [ImageOptim](https://imageoptim.com/mac).

**GIT workflow:**
1. Join the Git repo
2. Clone the product's spec repo to your local machine
3. Export specs for a feature from Sketch Measure, into the platform's Git folder
4. Add links to and images of your specs to the platform's index page
5. Push your changes and sync
6. Share the link with Pos and engineers

**Example:**  
[yo/ios-mail-specs](https://git.corp.yahoo.com/pages/aam/ios-mail-specs/)



- - -



# Necessary plugins and files

**Sketch Plug-ins:**  
[Artboard Tricks plugin](https://github.com/romannurik/Sketch-ArtboardTricks)  
[Import Symbols](https://github.com/kmerc/sketch-import-symbols)  
[Sketch Measure](https://github.com/utom/sketch-measure)  
[Sketch Palettes](https://github.com/andrewfiorillo/sketch-palettes)  
[Symbol Organizer](https://www.sketchpacks.com/sonburn/symbol-organizer)  
[Sync to Slides](https://github.com/websiddu/sync-to-slides)

**Files:**  
[Fuji Palette](https://drive.google.com/open?id=0B3XQlwtpWyzFd1dhVDN3VnhIbmc)  

**Apps:**  
[Colour Contrast Analyser for macOS](https://github.com/ThePacielloGroup/CCA-OSX)  
[Sketchpacks](https://www.sketchpacks.com)  
[ImageAlpha](https://pngmini.com/)  
[ImageOptim](https://imageoptim.com/mac)  
