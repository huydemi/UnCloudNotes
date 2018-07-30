# UnCloudNotes

This Core Data migrations tutorial discusses the many aspects of Core Data migrations by walking you through the evolution of a note-taking app’s data model. 

You’ll start with a simple app with only a single entity in its data model.

- Lightweight Migrations
- Manual Migrations
- Custom Manual Migrations
- Fully Manual Migrations

The Migration Process

- First, Core Data copies over all the objects from one data store to the next.
- Next, Core Data connects and relates all the objects according to the relationship mapping.
- Finally, enforce any data validations in the destination model. Core Data disables destination model validations during the data copy.

![screenshot](https://koenig-media.raywenderlich.com/uploads/2017/10/image9-1-282x500.png)

---

Source:

- [UIGestureRecognizer Tutorial: Getting Started](https://www.raywenderlich.com/162745/uigesturerecognizer-tutorial-getting-started)
