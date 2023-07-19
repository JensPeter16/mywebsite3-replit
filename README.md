The core classes, functions, and methods that will be necessary for the project are as follows:

1. `generate_cover_prompt(plot)`: Generates a prompt for the cover art description based on the book's plot.
2. `create_cover_image(plot)`: Creates the cover image for the book based on the provided plot.
3. `create_epub(title, author, chapters, cover_image_path)`: Creates an EPUB file with the specified title, author, chapters, and cover image.
4. `print_step_costs(response, model)`: Prints the step cost of the OpenAI API response based on the model used.
5. `generate_plots(prompt)`: Generates fantasy novel plots based on a given prompt.
6. `select_most_engaging(plots)`: Selects the most engaging plot from a list of generated plots.
7. `improve_plot(plot)`: Improves and refines a given plot.
8. `get_title(plot)`: Generates a title for the book based on the provided plot.
9. `write_first_chapter(plot, first_chapter_title, writing_style)`: Writes the first chapter of the book based on the plot, chapter title, and writing style.
10. `write_chapter(previous_chapters, plot, chapter_title)`: Writes the next chapter of the book based on the previous chapters, plot, and chapter title.
11. `generate_storyline(prompt, num_chapters)`: Generates a detailed storyline with chapters for the book based on the prompt and number of chapters.
12. `write_to_file(prompt, content)`: Writes the output for a given prompt to a file.
13. `write_fantasy_novel(prompt, num_chapters, writing_style)`: Writes a fantasy novel based on the prompt, number of chapters, and writing style.

Now let's proceed with creating the necessary files.

**main.py**

