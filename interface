public interface IRepository<T>
    {
        Task<FadActionResult<T>> InsertAsync(T model);
        Task<FadActionResult<T>> UpdateAsync(T model);
        Task<FadActionResult<T>> DeleteAsync(int id);
        Task<FadActionResult<T>> GetAsync(int id);
        Task<FadActionResult<T>> GetAllAsync();
    }
