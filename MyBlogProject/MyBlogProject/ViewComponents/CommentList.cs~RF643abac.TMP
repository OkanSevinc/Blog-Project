using Microsoft.AspNetCore.Mvc;
using MyBlogProject.Models;
using System;
using System.Collections.Generic;
using System.Linq;
using System.Threading.Tasks;

namespace MyBlogProject.ViewComponents
{
    public class CommentList : ViewComponent
    {
        public IViewComponentResult Invoke()
        {
            var commentValues = new List<UserComment>
            {
                new UserComment
                {
                    ID=1,
                    Username="Okan"
                },
                new UserComment
                {
                    ID=2,
                    Username="Furkan"
                },
                new UserComment
                {
                    ID=3,
                    Username="Oğuz"
                },
            };
            return View(commentValues);
        }
    }
}
