There are two things I want to do in Manifold, that I don’t know if we can do in the current grant…

1. I want to finish my zd/skunkworks branch, which will allow people to construct a text in the Manifold backend 
2. I want to incorporate MDX into that text construction process (https://mdxjs.com/) and start building interactive components that can be included in the text using MDX.
3. I want to build a library of simple but useful React components that can be used when building a Manifold text… for example, we might have a <Resource> component that you could embed in the markdown to show a resource inline, or we might have a <Quiz> component that could be used for a simple inline quiz.
4. I want that library to serve as a starting point for other people to build small, self-contained components that can be used when crafting a Manifold text, and eventually have an ecosystem of text components (visualizations, interactive pieces, youtube videos, whatever people can think of) that all render in the reader, and get us to a place where Manifold texts are really able to do things that can’t be done in ebooks currently
5. I want to then write a publishing mechanism that allows people to export one of these texts as an interactive EPUB (which may not work in many readers, but would push the boundaries of what the EPUB could do and would be within the spec)

In all this, I envision Manifold moving toward being more of an authoring platform, but one that is very, very different from Editoria. The goal would not be to recreate the word > epub traditional press publication workflow, because tools already exist for that—rather the goal would be to build an authoring tool that was “press compatible” but that was very much geared toward digital humanists and scholars, and embraced the kinds of interactivity that are pretty easy with modern javascript—something that gave them an authoring platform that went beyond word, rather than tried to replace it.

If we were to write a new grant proposal at some point, I think I would try to present the ease-of-installation and hosting work that I talked about today as very closely tied to this vision above, and as a holistic step toward making Manifold a more powerful tool for scholars.

![dog](./dog.jpg "Dog")
