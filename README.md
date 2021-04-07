Quikread Analytics Panel
=========
``` javascript
      schema: {
        isbn_number: {
          type: 'string',
          title: 'ISBN Number (*required)',
          required: true
        },
        book_title: {
          type: 'string',
          title: 'Book Title (*required)',
          required: true
        },
        author: {
          type: 'string',
          title: 'Author Name (*required)',
          required: true
        },
        small_description: {
          type: 'string',
          title: 'Small Description (*required)',
          required: true
        },
        imageURL: {
          type: 'string',
          title: 'Image URL (*required)',
          required: true
        },
        category: {
          type: 'array',
          title: 'Book category',
          items: {
            type: 'string',
            title: 'Choose Category (*required)',
            required: true,
            enum: ['Adventure', 'Business', 'Comic', 'Crime', 'Docufiction', 'Epistolary', 'Erotic', 'Fiction',
              'Fantasy', 'Historical', 'Horror', 'Magic', 'realism', 'Mystery', 'Paranoid', 'Philosophical',
              'Political', 'Romance', 'Saga', 'Satire', 'Science', 'Speculative', 'Superhero', 'Thriller',
              'Urban', 'Western'
            ]
          }
        },
        youtubeURL: {
          type: 'array',
          title: 'Youtube Links (*required)',
          items: {
            type: 'string',
            title: 'Enter Link',
            required: true
          }
        },
        podcastURL: {
          type: 'array',
          title: 'Podcast MP3 URLS',
          items: {
            type: 'string',
            title: 'Enter MP3 URL',
          }
        },
        download_url: {
          type: 'string',
          title: 'Book download link',
          required: true
        },

      }

```
